<template>
    <footer>By <a href="//ttam.co">Matt Bannon</a></footer>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style lang="scss" scoped>
    footer {
        font-family: 'Montserrat', sans-serif;
        height: 3em;
        line-height: 3em;
        margin-top: -3em;

        a {
            color: rgba(255, 255, 255, 0.7);
        }
    }
</style>
