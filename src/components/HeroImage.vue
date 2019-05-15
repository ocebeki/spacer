<template>
    <div class="heroImage">
    </div>
</template>

<script>
    export default {
        name: 'HeroImage',
    };

</script>
<style lang="scss" scoped>
    .heroImage {
        background-image: url(../assets/heroimage.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: 80% 0;
        z-index: -1;
        position: fixed;
        top: 0;
        width: 100%;
        height: 100vh;
        min-height: 100vh;
    }

</style>
