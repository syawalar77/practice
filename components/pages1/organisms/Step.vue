<template>
    <div class="container-step">
            <div class="step-one">
                <img class="step-one-image" src="~/assets/image/image 13.png" alt="">
                <h2>Start with step one</h2>
                <p class="step-one-paragraf">nunc mattis feugiat ex scelerisque congue.</p>
            </div>
            <div class="easy-to-scan">
                <img class="easy-to-scan-image" src="~/assets/image/image 8.png" alt="">
                <h2>keep it easy to scan</h2>
                <p class="easy-to-scan-paragraf">Nam ut justro placerat, eleifend sem at, finibus velit.</p>
            </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.container-step {
    display: flex;
    justify-content: space-evenly;
    text-align: center;
    margin-top: 150px;
}
.step-one-image,
.easy-to-scan-image {
    border-radius: 50px;
}
.step-one-paragraf,
.easy-to-scan-paragraf {
    font-size: 18px;
}

@media (max-width: 382px) {
    .container-step {
        display: block;
        width: 90%;
        margin-left: 5%;
        margin-top: 50px;
    }
    .easy-to-scan-image {
        margin-top: 30px;
    }
}

</style>