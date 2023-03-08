<template>
  <section class="relative overflow-hidden">

    <!-- Bg -->
    <div class="absolute inset-0 bg-green-600 pointer-events-none -z-10" aria-hidden="true"></div>

    <!-- Illustration -->
    <div class="absolute left-1/2 -translate-x-1/3 md:-translate-x-1/2 pointer-events-none -z-10" aria-hidden="true">
      <!-- Had to place the SVG in the public folder, and here is why:
      Ref: https://github.com/vitejs/vite/issues/7062 -->
      <object type="image/svg+xml" data="/hero-illustration.svg" width="1440" height="1214"></object>
    </div>

    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="pt-28 pb-16 md:pt-40 md:pb-20">

        <!-- Hero content -->
        <div class="max-w-3xl mx-auto text-center">

          <h1 class="h1 font-cabinet-grotesk text-white mb-2" data-aos="fade-up"> ShagBai</h1>
          <h2 class="h2 font-cabinet-grotesk text-white mb-2" data-aos="fade-up"> Celebrating Culture and Supporting Our Community</h2>
          <p class="text-lg md:text-xl text-white text-opacity-80 mb-8" data-aos="fade-up" data-aos-delay="100">Join us in celebrating Culture while supporting our very own people.</p>
          <div data-aos="fade-up" data-aos-delay="200">
            <router-link class="mx-4 inline-flex items-center text-white bg-gray-900 hover:bg-gray-800 group" to="/schedule-call">
              Welcome to the official website of the ShagBai!
            
              
            </router-link>
          </div>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero',
}
</script>