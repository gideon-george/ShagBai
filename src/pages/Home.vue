<template>
  <div className="flex flex-col min-h-screen overflow-hidden">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <Hero />
      <Explainer />
      <Features01 />
      <Features02 />
      <Services />
      <Testimonial />
      <Cta />

    </main>
    
    <!-- Site footer -->
    <Footer />    

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import Hero from '../partials/Hero.vue'
import Clients from '../partials/Clients.vue'
import Explainer from '../partials/Explainer.vue'
import Features01 from '../partials/Features01.vue'
import Features02 from '../partials/Features02.vue'
import Services from '../partials/Services.vue'
import Testimonial from '../partials/Testimonial.vue'
import Cta from '../partials/Cta.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Clients,
    Explainer,
    Features01,
    Features02,
    Services,
    Testimonial,
    Cta,
    Footer
},
}
</script>