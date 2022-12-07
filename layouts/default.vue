<template>
    <div>
        <Navbar />
        <SliderVue />
        <SezonunTrendleriVue />
        <ContainerVue />
        <KoleksiyonlarVue />
        <FavoriModellerSliderVue />
        <Container2Vue />
        <Container3Vue />
        <FooterVue />
        <Footer2Vue />
    </div>
</template> 
<script>
import Navbar from '../components/navbar.vue';
import SezonunTrendleriVue from '../components/SezonunTrendleri.vue';
import ContainerVue from '../components/Container.vue';
import KoleksiyonlarVue from '../components/Koleksiyonlar.vue'
import Container2Vue from '../components/Container2.vue';
import FooterVue from '../components/Footer.vue'
import SliderVue from '../components/Slider.vue';
import Container3Vue from '../components/Container3.vue';
import Footer2Vue from '../components/Footer2.vue'
import FavoriModellerSliderVue from '../components/FavoriModellerSlider.vue';

export default {
    name: "IndexPage",
    components: { Navbar, SezonunTrendleriVue, ContainerVue, KoleksiyonlarVue, Container2Vue, FooterVue, SliderVue, Container3Vue, Footer2Vue, FavoriModellerSliderVue }
}
</script>