<template>
    <section class="icons">
        <div v-for="(link, i) in linksImage" :kei="i" class="my-container icon">
            <img :src="getImagePath(`../assets/img/${link.url}`)" class="img-icon">
            <a href="#">{{ link.text }}</a>
        </div>
    </section>
</template>

<script>
export default {
    data() {
        return {
            linksImage: [
                {
                    text: 'digital comics',
                    url: 'buy-comics-digital-comics.png'
                },
                {
                    text: 'dc merchandise',
                    url: 'buy-comics-merchandise.png'
                },
                {
                    text: 'subscription',
                    url: 'buy-comics-subscriptions.png'
                },
                {
                    text: 'comic shop locator',
                    url: 'buy-comics-shop-locator.png'
                },
                {
                    text: 'dc power visa',
                    url: 'buy-dc-power-visa.svg'
                }
            ]
        }
    },
    methods: {
        getImagePath(imgPath) {
            return new URL(imgPath, import.meta.url).href;
        }
    }
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables' as *;

.icons {
    background-color: $DcBlue;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1rem;

    .icon {
        display: flex;
        justify-content: center;
        align-items: center;

        .img-icon {
            width: 40px;
            margin: 0 10px;
        }



        a {
            text-decoration: none;
            color: white;
            font-size: 1.1rem;
            text-transform: uppercase;
        }
    }

    .icon .img-icon:nth-child(4) {
        width: 20px;
    }
}
</style>
sezione-blu.txt
2 KB