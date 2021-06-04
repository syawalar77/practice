<template>
    <div class="container-title">
        <button class="btn btn-primary"
            @click="$emit('click-button')"
        >
            {{ msg }}

        </button>
        
    </div>
</template>

<script>
export default {
    props: {
        msg: {
            default: 'Seakun.id',
            type: String
        }
        
    }

}
</script>

<style>

</style>