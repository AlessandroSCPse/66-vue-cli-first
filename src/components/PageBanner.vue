<template>
    <section>
        <img :src="imgSrc" alt="">

        <div class="banner-text">
            <h3>Titolo del banner</h3>
        </div>
    </section>
</template>

<script>
export default {
    name: "PageBanner",
    data() {
        return {
            imgSrc: require('../assets/img/saturn.jpg')
        };
    }
}
</script>

<style lang="scss" scoped>

section {
    height: 500px;
    position: relative;
    // background-image: url('../assets/img/saturn.jpg');
}

img {
    height: 100%;
    object-fit: cover;
}

.banner-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
}

</style>