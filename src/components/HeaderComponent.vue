<template>
    <header>
        <div class="wrapper container">
            <a href="#">
                <img class="logo-dc" src="../assets/img/dc-logo.png" alt="">
            </a>
            <nav>
                <ul class="ul-header">
                    <li v-for="(link, index) in NavItems" :key="index">
                        <a href="link.url" :class="{ 'active': link.curent }">{{ link.text }}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>

export default {
    data() {
        return {


            NavItems: [
                {
                    text: "Characters",
                    url: "#",
                    current: false,
                },
                {
                    text: "Comics",
                    url: "#",
                    current: false,
                },
                {
                    text: "Movies",
                    url: "#",
                    current: false,
                },
                {
                    text: "TV",
                    url: "#",
                    current: false,
                },
                {
                    text: "Games",
                    url: "#",
                    current: false,
                },
                {
                    text: "Collectibles",
                    url: "#",
                    current: false,
                },
                {
                    text: "Videos",
                    url: "#",
                    current: false,
                },
                {
                    text: "Fans",
                    url: "#",
                    current: false,
                },
                {
                    text: "News",
                    url: "#",
                    current: false,
                },
                {
                    text: "Shop",
                    url: "#",
                    current: false,
                },
            ]

        }
    }
}


</script>

<style lang="scss">
@use '../assets/styles/partials/variables' as *;

header {
    height: 200px;

}



.container {
    width: 80%;
    margin: 0 auto;
}

.wrapper {
    display: flex;
    justify-content: space-between;



    align-content: center;
    align-items: center;
}

nav {
    height: 100%;
}

.ul-header {
    list-style: none;
    display: flex;




    li {

        &.active,
        &:hover,
        &:active {

            box-sizing: border-box;
            border-bottom: 5px solid $DcBlue;

            a {
                color: $DcBlue;
            }
        }


        a {
            line-height: 195px;
            font-size: 14px;
            margin-right: 10px;
            text-transform: uppercase;
            font-weight: bold;
            color: black;
            text-decoration: none;
        }

    }


}
</style>