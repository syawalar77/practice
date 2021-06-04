<template>
    <div class="container-pages">
        <Intro/>
        <Step/>
        <Bigcompany/>
        <NewsCard/>
        <Footer/>
        <Popup/>
        <ScrollToTop/>
    </div>
</template>

<script>
import Intro from '~/components/pages1/organisms/IntroSection.vue'
import Step from '~/components/pages1/organisms/Step.vue'
import Bigcompany from '~/components/pages1/organisms/BigCompanySection.vue'
import NewsCard from '~/components/pages1/mollecules/NewsCardSection.vue'
import Footer from '~/components/atoms/Footer.vue'
import Popup from '~/components/pages1/mollecules/Popup.vue'
import ScrollToTop from '~/components/atoms/ButtonScroll.vue'
export default {
    components: {
        Intro,
        Step,
        Bigcompany,
        NewsCard,
        Footer,
        Popup,
        ScrollToTop,
    }

}
</script>

<style>

</style>