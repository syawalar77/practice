<template>
    <div>
        <NewsDetail/>
        <Footer/>
        <ButtonScroll/>
    </div>
</template>

<script>
import NewsDetail from '~/components/pages2/NewsDetail.vue'
import Footer from '~/components/atoms/Footer.vue'
import ButtonScroll from '~/components/atoms/ButtonScroll.vue'
export default {
    components: {
        NewsDetail,
        Footer,
        ButtonScroll,
    }
}
</script>

<style>

</style>