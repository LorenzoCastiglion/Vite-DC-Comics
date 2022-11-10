<template>
    <div class="bg-main">

        <div class="wrapper-main">
            <p> &rarr; Content Goes Here! &larr; </p>
        </div>

    </div>
</template>

<script>

</script>

<style lang="scss">
@use '../assets/styles/partials/variables' as *;

.wrapper-main {
    display: flex;
    justify-content: center;
    margin: 0 auto;
    width: 80%;
    height: 200px;
    align-content: center;
    align-items: center;

    p {
        color: white;
        font-size: 24px;
        font-weight: bold;
    }
}

.bg-main {
    background-color: $DcDarkGrey;
}
</style>