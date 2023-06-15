<template>
    <section>
        <h1>Featured Product</h1>
        <div class="container"></div>
    </section>
</template>

<script>
export default {
    name: "Featured"
}
</script>

<style scoped>
section {
    width: 100%;
    height: auto;
    border: 2px solid green;
    padding: 50px;
}
h1 {
    font-size: 2rem;
}
.container {
    width: 100%;
    height: 500px;
    border: 4px solid red;
}
</style>