<template>


<CustomLayout>
  <section id="lander" class="">
    <Lander></Lander>
  </section>
  <section class="about">
    <About />
  </section>
  <section>
    <Gallery />
  </section>
  <section id="">
    <Contact />
  </section>

</CustomLayout>

</template>

<script>
import CustomLayout from '../layouts/CustomLayout.vue'
import Lander from '../components/Sections/Lander.vue'
import About from '../components/Sections/About.vue'
import Gallery from '../components/Sections/Gallery.vue'
import Contact from '../components/Sections/Contact.vue'
export default {
  components: { 
    CustomLayout ,
    Lander,
    About,
    Gallery,
    Contact
  },
  metaInfo: {
    title: 'About us'
  }
}
</script>
