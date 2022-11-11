<template>
    <div class="bg-main ">

        <div class="container  ">
            <div class="current">
                <span>current series</span>
            </div>
            <div class="wrapper-main">
                <div class="card" v-for="(comic, index) in comics" :key="index">

                    <div class="img-wrap">
                        <img :src="comic.thumb" :alt="comic.series">
                    </div>
                    <p> {{ comic.series }}</p>

                </div>
            </div>

            <div class="load-container">
                <a class="load" href="#">load more</a>
            </div>
        </div>

    </div>
</template>

<script>
import { cover } from '../data/comics';
export default {
    name: 'MainComponent',
    data() {
        return {
            comics: cover
        }
    }

}

</script>

<style lang="scss">
@use '../assets/styles/partials/variables' as *;

.current {
    position: absolute;
    text-transform: uppercase;
    top: -10px;

    span {
        padding: 10px;
        color: white;
        background-color: $DcBlue;
        font-size: 24px;
        font-weight: bold;

    }

}

.load-container {
    text-align: center;
    padding: 25px 0;
}

.load {
    text-transform: uppercase;
    color: white;
    background-color: $DcBlue;
    padding: 10px 20px;
    text-decoration: none;


    &:hover {
        filter: invert(1);
    }

}



.card {

    margin-top: 50px;
    width: calc(100% / 6);
}

.img-wrap {
    width: 200px;
    height: 200px;
    overflow-y: hidden;

}

.wrapper-main {
    display: flex;
    flex-wrap: wrap;







    p {
        width: 80%;
        color: white;
        font-size: 16px;

    }
}

.bg-main {
    position: relative;
    background-color: $DcDarkGrey;
}
</style>