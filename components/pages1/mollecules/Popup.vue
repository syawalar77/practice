<template>
    <div class="container-popup">
        <button @click="popUp()" class="button-close-popup" id="lates">x</button>
        <p id="popup">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus repellat sequi, consequuntur dicta maiores repudiandae culpa animi nostrum ipsam odit minus unde in reprehenderit tempore minima voluptate fugit reiciendis. Aspernatur.
        </p>
        <div>
            <input type="text">
            <button>Submit</button>
        </div>
        
    </div>
</template>

<script>
export default { 
    mounted() {
        this.showPopup()
    },
    methods: {
        popUp() {
            $(".container-popup").fadeOut("slow")
        },
        showPopup() {
            setInterval(function() {
                $(".container-popup").fadeIn("slow")
            }, 6000)
        }
    },

}
</script>

<style>
.container-popup {
    width: 350px;
    position: fixed;
    bottom: 10px;
    left: 10px;
    /* z-index: 99; */
    background-color: rgb(134, 208, 193, 0.8);
    color: white;
    padding: 15px;
}
.button-close-popup {
    color: white;
    background-color: transparent;
    border: none;
    float: right;
} 
</style>