<template>
  <div>
    <NavTop/>
    <AgileHeroCarousel/>
    <Tutorial/>
    <Footer/>
  </div>
</template>

<script>
import Footer from "~/components/Footer.vue";
export default { components: { Footer } };
</script>

<style>
body {
  font-family: Roboto;
}
.color-basic {
  color: #0e5d90;
}
.text-color-basic {
  color: #082e46;
}

.Bg-PrimaryColor {
  background: #2c97dd;
}
.Text-PrimaryColor {
  color: #2c97dd;
}
</style>
