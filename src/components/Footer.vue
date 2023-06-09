<template>
    <section>
        <div class="sub">
            <div class="sub1">
                <h4>SUBSCRIBE TO OUR NEWSLETTER</h4>
                <div class="mail"></div>
            </div>
            <div class="sub1" style="border-right: 0px;">
                <div class="socials">
                    <h4>JOIN US ON</h4>
                    <div class="socs"></div>
                    <div class="socs"></div>
                    <div class="socs"></div>
                </div>
            </div>
        </div>
        <hr style="border: 2px solid green" />
        <div class="last">
            <div class="one">
                <h4>TERMS & CONDITION POLICY</h4>
            </div>
            <div class="two"></div>
            <div class="three">
                <h4>© 2023, Bamboo All Rights Reserved.</h4>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    border: 2px solid red;
    width: 100%;
    height: auto;
    padding: 20px 1px;
}

h1 {
    font-size: 60px;
}
.sub {
    width: 100%;
    height: auto;
    border: 2px solid red;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
}
.sub1 {
    width: 50%;
    height: 100px;
    border-right: 3px solid blue;
    padding: 20px;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
}
.mail {
    border: 1px solid green;
    width: 250px;
    height: 36px;
    border-radius: 18px;
    position: relative;
    top: 12px;
    left: 15px;
}
.socials {
    width: 400px;
    height: auto;
    border: 1px solid red;
    margin: 0px auto;
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.socs {
    width: 40px;
    height: 40px;
    border: 1px solid blue;
    margin: 10px 6px;
    border-radius: 50%;
}
.last {
    height: 200px;
    width: 100%;
    border: 2px solid blue;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    padding: 70px 0px;
    margin-top: 50px;
}
.one {
    width: 300px;
    height: auto;
    border: 1px solid red;
}
.two {
    width: 250px;
    height: 100px;
    border: 1px solid red;
    position: relative;
    bottom: 25px;
}
.three {
    width: 300px;
    height: auto;
    border: 1px solid red;
}





</style>