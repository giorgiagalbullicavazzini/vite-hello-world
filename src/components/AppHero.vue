<!-- Jumbotron data -->
<script>
export default {
    data() {
        return {
            imageVite: 'vite-jumbotron.png'
        }
    },
    methods: {
        getImagePath: function (imgPath) {
            return new URL(imgPath, import.meta.url).href;
        }
    }
}
</script>
<!-- // Jumbotron data -->

<!-- HTML -->
<template>
    <div id="jumbotron">
        <img :src="getImagePath(`../assets/${imageVite}`)" alt="Immagine promozionale di Vite">
    </div>
</template>
<!-- // HTML -->

<!-- CSS -->
<style scoped>
#jumbotron {
    margin: auto;
    max-width: 50rem;
    width: 80%;
}

img {
    display: block;
    width: 100%;
}
</style>
<!-- // CSS -->