
<template>
  <div>
    <Navbar />
    <SezonunTrendleriVue />

  </div>
</template> 
<script>
import Navbar from '../components/navbar.vue';
import SezonunTrendleriVue from '../components/SezonunTrendleri.vue';

export default {
  name: "IndexPage",
  components: { Navbar, SezonunTrendleriVue }
}
</script>