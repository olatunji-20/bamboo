<template>
    <section>
        <h1>Bamboo Products</h1>
        <ul>
            <li>CHAIR</li>
            <li>CABINET</li>
            <li>SOFA</li>
            <li>BENCH</li>
        </ul>
        <div class="small">
            <div class="subsmall">
                <div class="prod"></div>
                <div class="prod"></div>
                <div class="prod"></div>
                <div class="prod"></div>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    border: 5px solid blue;
    width: 100%;
    height: 500px;
    text-align:center;
    padding: 40px 0px 550px;
}
h1 {
    font-size: 30px;
}
li {
    list-style-type: none;
    display: inline-block;
    margin: 0px 25px;
    font-weight: bolder;
}
.small {
    border: 2px solid red;
    height: 260px;
    width: 80%;
    margin: 50px auto 0px;
    padding: 5px;
    overflow: auto;
}
.subsmall {
    border: 1px solid green;
    height: 210px;
    width: 1500px;
    padding: 4px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.prod {
    border: 1px solid blue;
    width: 300px;
    height: 200px;
    border-radius: 5px;
}
</style>