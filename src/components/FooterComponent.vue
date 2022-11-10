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
            <div class="container"></div>
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
}

.top {
    height: 300px;
    overflow: hidden;
    display: flex;
    justify-content: space-between;
}

.ul-footer {

    display: flex;
    flex-flow: column wrap;
}

h3 {
    color: white;
    text-transform: uppercase;
    font-weight: bold;
}

li {
    color: $DcGrey;
}
</style>