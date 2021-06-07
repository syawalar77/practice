<template>
    <div class="container-big-company">
            <div class="big-company-left">
                <img 
                    class="big-company-image"
                    src="~/assets/image/coding.png" 
                    alt="image not found"
                    style="max-width:400px;"
                >
            </div>
            <div class="big-company-right">
                <h1 class="big-company-right-title">Big company announcement</h1>
                <p class="big-company-right-paragraf">
                    Big company announcement or simple sub-header taking two or more lines
                </p>
                <!-- <NuxtLink to="/detail"> -->
                    <Button
                        titleBtn="Link 2"
                        @click-button="changePages"
                    />
                <!-- </NuxtLink> -->
            </div>
        </div>
</template>

<script>
import Button from '~/components/atoms/Button.vue'
export default {
    components: {
        Button,
    },
    data() {
        return {
        }
    },
    methods: {
        changePages() {
            this.$router.push('/detail')
        }
    }

}
</script>

<style>
.container-big-company {
    width: 80%; 
    margin-left: 10%;
    display: flex;
    justify-content: space-evenly;
    margin-top: 100px;
}
.big-company-right,
.big-company-left {
    width: 400px;
}
.big-company-image {
    width: 500px!important;
}
.big-company-right-title {
    font-size: 42px;
}
.big-company-right-paragraf {
    font-size: 22px;
}
.big-company-right-button {
    background-color: #86d0c1;
    border: 1px solid white;
    color: white;
    width: 150px;
    height: 40px;
    margin-top: 10px;
}
@media (max-width: 719px) {
    .container-big-company {
        width: 80%;
        margin-left: 10%;
        justify-content: center;
        display: block;
    }
    .big-company-left,
    .big-company-right,
    .big-company-image {
        width: 100%!important;
        text-align: center;
    }
    .big-company-right-title {
        font-size: 32px;
    }
    .big-company-right-paragraf {
        font-size: 16px;
    }
}
</style>