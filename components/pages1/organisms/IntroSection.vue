<template>
    <div class="conntainer-introduction">
        <div class="introduction-container">
            <div class="introduction">
                <div class="introduction-left">
                    <h1 class="introduction-title">Showcase your thought provoking topics and ideas</h1>
                    <p class="introduction-paragraf">
                        Big company announcement or simple sub-header taking two or more lines
                    </p>
                    <Button
                        titleBtn="Link 2"
                        @click-button="changePages"
                    />
                </div>
                <div class="introduction-right">
                    <img 
                        class="introduction-image"
                        src="~/assets/image/intro.png" 
                        alt="image not found"
                        style="max-width:400px;"
                    >
                </div>
            </div>

        </div>

    </div>
</template>

<script>
import Button from '~/components/atoms/Button.vue'
export default {
    components: {
        Button,
    },
    methods: {
        changePages() {
            this.$router.push('/detail')
        }
    }

}
</script>

<style>
.introduction-container {
    background-color: #86d0c1;
    margin: 0;
    padding: 0;
}
.introduction-title,
.introduction-paragraf {
    color: white;
}
@media (min-width :719px) {
    .introduction {
        justify-content: space-between;
        display: flex; 
        width: 80%;
        margin-left: 10%;
    }
    .introduction-title {
        font-size: 42px;
        color: white;
    }
    .introduction-image {
        width: 400px!important;
    }
    .introduction-paragraf {
        font-size: 22px;
        color: white;
    }
    .introduction-left, .introduction-right {
        width: 400px;
        margin-top: 100px;
        /* padding: 150px 0; */
    }
}
@media (max-width: 719px) {
    .introduction-container {
        width: 100%;
        padding-top: 10px;
    }
    .introduction {
        width: 100%!important;
        /* border: 1px solid; */
        /* margin-left: 10%; */
        justify-content: center;
        text-align: center;
    }
    .introduction-image {
        width: 350px!important;
    }
}
@media (max-width: 382px) {
    .introduction {
        display: inline-block;
        width: 100%;
        /* margin-top: 50px; */

    }
    .introduction-container {
        margin-top: -20px;
    }
    .introduction-left {
        width: 100%!important;
        /* margin-left: 5%; */
        
    }
    .introduction-image {
        max-width: 100%!important;
        /* margin-top: 50px; */
        text-align: center;
    }
}
</style>