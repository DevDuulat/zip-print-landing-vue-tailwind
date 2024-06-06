<template>
  <div id="app">
    <MainHeader />
    <MainPromo />
    <MainServices />
    <MainPortfolio />
    <CtaSection />
    <ContactForm />
    <MainFooter />
  </div>
</template>
<script>
import MainHeader from './components/MainHeader.vue'
import MainPromo from './components/MainPromo.vue'
import MainServices from './components/MainServices.vue'
import MainPortfolio from './components/MainPortfolio.vue'
import CtaSection from './components/CtaSection.vue'
import ContactForm from './components/ContactForm.vue'
import MainFooter from './components/MainFooter.vue'


export default {
  name: 'App',
  components: {
    MainHeader,
    MainPromo,
    MainServices,
    MainPortfolio,
    CtaSection,
    ContactForm,
    MainFooter
  }
}
</script>

