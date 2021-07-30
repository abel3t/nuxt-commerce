<template>
  <div>
    <Menubar />
    <nuxt />
    <Footer />
  </div>
</template>
<script>
import Footer from './Footer';
import Menubar from './Menubar';
export default {
  components: { Menubar, Footer }
};
</script>
