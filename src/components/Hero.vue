<template>
    <section>
        <h1>HERO</h1>
    </section>
</template>

<script>
export default {
    name: "Hero"
}
</script>

<style scoped>
section {
    position: relative;
    top: 0px;
    z-index: 1;
    border: 2px solid red;
    width: 100%;
    /* height: calc(100vh - 100px); */
    height: 100vh;
    background-image: url(../assets/hero.png);
    background-size: cover;
}
h1 {
    margin-top: 300px;
}
</style>