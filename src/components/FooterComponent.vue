<template>

    <footer>
        <div class="footer-bg-top">
            <div class="container top">

                <div class="lista">

                    <ul>
                        <h3>dc comics</h3>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>

                        <br>

                        <ul>
                            <h3>shop</h3>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </ul>



                    <ul>
                        <h3>DC</h3>
                        <li><a href="#">Term Of Use</a></li>
                        <li><a href="#">Privace Policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Talent Workshop</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>

                    <ul>
                        <h3>sites</h3>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Talent Workshop</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>

                </div>

                <div>
                    <img id="bg-logo" src="../assets/img/dc-logo-bg.png" alt="">
                </div>

            </div>
        </div>
        <div class="footer-bg-btm">
            <div class="container foot-flex">
                <button>SIGN-UP NOW!</button>
                <div class="foot-flex">
                    <h2>FOLLOW US</h2>
                    <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a>
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
    background-image: url(../assets/img/footer-bg.jpg);
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
    align-items: center;
    align-content: center;

}

.lista {
    gap: 30px;
    display: flex;
    flex-flow: row wrap;

    ul {
        list-style: none;
    }

    a {
        font-size: 14px;
        color: $DcGrey;
        text-decoration: none;
    }
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


// seconda

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