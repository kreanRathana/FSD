<template>
  <v-app>
    <CategoryPlace/>
    <Navbar/>
    <ImageSlide/>
    <Footer/>
    <FooterWeb/>

  </v-app>
</template>

<script>
import FooterWeb from './components/WebFooter'
import Footer from './components/Footer'
import ImageSlide from './components/ImageSlider';
import Navbar from './components/Navbar'
import CategoryPlace from './components/CategoriesPlace'
export default {
  name: 'App',

  components: {
    FooterWeb,
    ImageSlide,
    Navbar,
    Footer,
    CategoryPlace
  },

  data: () => ({
    //
  }),
};
</script>
