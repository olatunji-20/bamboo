<template>
    <section>
        <div class="nav-one"></div>
        <div class="nav-two"></div>
        <div class="nav-three">
            <div class="search"></div>
            <div class="cart"></div>
        </div>
    </section>
</template>

<script>
export default {
    name: "NavBar"
}
</script>

<style scoped>
section {
    border: 2px solid red;
    height: 120px;
    width: 100%;
    background: powderblue;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 35px 60px;
    position: absolute;
    top: 0;
    z-index: 2;
}
.nav-one {
    width: 70px;
    height: 50px;
    border: 1px solid blue;
}
.nav-two {
    width: 200px;
    height: 60px;
    border: 1px solid red;
    position: relative;
    bottom: 5px;
}
.nav-three {
    width: 120px;
    height: 50px;
    border: 1px solid green;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
}
.search, .cart {
    border: 1px solid blue;
    height: 50px;
    width: 45px;
}
</style>