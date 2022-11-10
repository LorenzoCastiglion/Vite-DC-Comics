<template>

    <footer>
        <div class="footer-bg-top">
            <div class="container wrapper top">
                <div>


                </div>
                <div>
                    <img id="bg-logo" src="../assets/img/img/dc-logo-bg.png" alt="">
                </div>

            </div>
        </div>
        <div class="footer-bg-btm">
            <div class="container foot-flex">
                <button>SIGN-UP NOW!</button>
                <div class="foot-flex">
                    <h2>FOLLOW US</h2>
                    <a href="#"><img src="../assets/img/img/footer-facebook.png" alt=""></a>
                    <a href="#"><img src="../assets/img/img/footer-twitter.png" alt=""></a>
                    <a href="#"><img src="../assets/img/img/footer-youtube.png" alt=""></a>
                    <a href="#"><img src="../assets/img/img/footer-pinterest.png" alt=""></a>
                    <a href="#"><img src="../assets/img/img/footer-periscope.png" alt=""></a>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

</script>

<style lang="scss">
@use '../assets/styles/partials/variables' as *;

footer {

    height: 300px;
}

.footer-bg-top {

    height: 100%;
    background-image: url(../assets/img/img/footer-bg.jpg);
}

#bg-logo {
    height: 400px;
}

.footer-bg-btm {
    height: 100px;
    background-color: $DcDarkGrey;
    display: flex;
    align-items: center;
    align-content: center;
}

.top {
    height: 300px;
    overflow: hidden;
    display: flex;
    justify-content: space-between;
}

.ul-footer {

    display: flex;
    flex-flow: column;
}

h3 {
    color: white;
    text-transform: uppercase;
    font-weight: bold;
}

li {
    color: $DcGrey;
}

button {
    font-size: 20px;
    border: 2px solid $DcBlue;
    background-color: transparent;
    color: white;
    padding: 10px;
}

.foot-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    align-content: center;

    a {
        padding: 0 5px;
    }

    h2 {
        font-size: 20px;
        color: $DcBlue;
        padding-right: 5px;
    }
}
</style>