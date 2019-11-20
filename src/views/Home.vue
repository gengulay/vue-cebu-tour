<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/HRI-Bohol-Cebu-Tours-logo-1_optimized-1.png">
    <FirstSection/>
    <SecondSection/>
    <ThirdSection/>
    <FourthSection/>
    <BoholTour/>
    <FirstCarousel/>
    <TestimonialSection/>
    <Footer/>
  </div>
</template>

<script>
  // @ is an alias to /src
  import FirstSection from "@/components/FirstSection.vue";
  import SecondSection from "../components/SecondSection";
  import ThirdSection from "../components/ThirdSection";
  import FourthSection from "../components/FourthSection";
  import BoholTour from "../components/BoholTour";
  import FirstCarousel from "../components/FirstCarousel";
  import TestimonialSection from "../components/TestimonialSection";
  import Footer from "../components/Footer";

  export default {
    name: 'home',
    components: {
      BoholTour,
      FourthSection,
      ThirdSection,
      SecondSection,
      FirstSection,
      FirstCarousel,
      TestimonialSection,
      Footer
    }
  }
</script>
