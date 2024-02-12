<template>
    <div class="choicePet">
        <div class="menu"><img src="./icons/list-view-icon.svg"></div>


        <div class="dogImg">
            <img class="dog" src="../image/35634172_06.jpg" alt="dog">
            <h3>DOG</h3>
        </div>
        <div class="catImg">
            <img class="cat" src="../image/23441609_6778462.svg" alt="cat">
            <h3>CAT</h3>
        </div>

    </div>
    <div class="footer">
        <p>Terms of Use</p>
        <p>Shipping</p>
        <p>Contact</p>
    </div>
</template>

<script>

</script>

<style scoped>
.menu {
    position: fixed;
    right: 15px;
    top: 50px;
    width: 50px;
    height: 50px;

}

.choicePet {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 80vh;
    /* background-color: red; */

}

.dogImg,
.catImg {
    width: 268px;
    height: 287px;

}

h3 {
    padding: 10px;
    text-align: center;

}

img {
    display: block;
    width: 100%;
    height: 100%;

}

.dog,
.cat {
    border-radius: 135px;
}

.footer {
    width: 100%;
    height: 20vh;
    text-align: center;
}

p {
    height: 30%;
}</style>