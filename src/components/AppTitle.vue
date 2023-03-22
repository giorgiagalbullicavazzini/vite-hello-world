<!-- Title data -->
<script>
export default {
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}
</script>
<!-- // Title data -->

<!-- HTML -->
<template>
    <h1>{{ title }}</h1>
</template>
<!-- // HTML -->

<!-- CSS -->
<style scoped>
h1 {
    /* Text gradient */
    background: -webkit-linear-gradient(rgba(156, 252, 248, 1) 11.2%, rgba(110, 123, 251, 1) 91.1%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

    /* Properties */
    font-family: "Lato";
    font-size: 4.5rem;
    font-style: italic;
    margin-top: 3.125rem;
    text-align: center;
}
</style>
<!-- // CSS -->