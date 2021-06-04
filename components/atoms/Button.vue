<template>
    <div class="container-button">
        <button 
            class="button"
            @click="$emit('click-button')"
        > 
            {{ titleBtn }}
        </button>
    </div>
</template>

<script>
export default {
    props: {
        titleBtn: {
            default: 'submit',
            type: String,
        }
    }

}
</script>

<style>
.button {
    background-color: #86d0c1;
    border: 1px solid white;
    color: white;
    width: 150px;
    height: 40px;
    margin-top: 10px;
}

</style>