<template>
  <section>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-16">
          <h2 class="h2 mb-5 font-cabinet-grotesk">Shagbai Festival Returns with a Purpose.</h2>
          <h3 class="h4 mt-10 font-cabinet-grotesk">Helping Our Community and Supporting those Affected by the Mai Tangale Crisis.</h3>
        </div>

        <!-- Section image -->
        <div class="flex justify-center pb-12 md:pb-16" data-aos="fade-up">
          <div class="relative inline-flex justify-center items-center">
            <p> </p>
            <div class="absolute">
              
            </div>
          </div>

          <Modal id="video-modal" ariaLabel="modal-headline" :modalOpen="videoModalOpen" @close-modal="videoModalOpen = false">
            <iframe class="w-full aspect-video" src="https://player.vimeo.com/video/174002812" title="Video" allowFullScreen></iframe>
          </Modal>
        </div>

        <!-- Steps -->
        <div class="relative pb-12">

          <!-- Line -->
          <div class="hidden lg:block absolute top-4 left-32 right-32 mt-px h-0.5 bg-gray-200 -z-10" aria-hidden="true"></div>

          <!-- Grid -->
          <div class="max-w-sm mx-auto grid gap-12 sm:grid-cols-2 sm:max-w-3xl lg:grid-cols-4 lg:max-w-none items-start">

            <!-- #1 -->
            <div class="text-center">
              <div class="w-9 h-9 bg-gray-900 border-2 border-white text-white text-[15px] font-bold rounded-full inline-flex items-center justify-center mb-3">1</div>
              <h3 class="font-cabinet-grotesk font-bold text-lg">Youth and Culture of Tangle</h3>
              <div class="text-gray-500">This dedicated section of the festival highlighted the talents and rich cultural heritage of the young people of Tangle through exciting performances of traditional dance and music. It was a celebration of the next generation of Tangle and their commitment to preserving the cultural traditions of their community.</div>
            </div>

            <!-- #2 -->
            <div class="text-center">
              <div class="w-9 h-9 bg-gray-900 border-2 border-white text-white text-[15px] font-bold rounded-full inline-flex items-center justify-center mb-3">2</div>
              <h3 class="font-cabinet-grotesk font-bold text-lg">Youth and Politics in Tangle</h3>
              <div class="text-gray-500">A thought-provoking panel discussion brought together young leaders from Tangle to delve into the important topic of youth involvement in shaping the political future of their community. The discussion provided a platform for the voices of Tangle's young leaders to be heard and their ideas to be shared, with a focus on how they can drive positive change and shape the political landscape of their community.</div>
            </div>

            <!-- #3 -->
            <div class="text-center">
              <div class="w-9 h-9 bg-gray-900 border-2 border-white text-white text-[15px] font-bold rounded-full inline-flex items-center justify-center mb-3">3</div>
              <h3 class="font-cabinet-grotesk font-bold text-lg">Dance and Songs of Tangale</h3>
              <div class="text-gray-500">This spectacular performance showcase highlighted the traditional dance and music of Tangale, featuring a diverse array of artists who captivated the audience with their talents. From pulse-pounding drum beats to mesmerizing dances, the Dance and Songs of Tangale performance was a celebration of the rich cultural heritage of the Tangle community, and a must-see experience for anyone interested in the traditions and art forms of Tangale.</div>
            </div>

            <!-- #4 -->
            <div class="text-center">
              <div class="w-9 h-9 bg-gray-900 border-2 border-white text-white text-[15px] font-bold rounded-full inline-flex items-center justify-center mb-3">4</div>
              <h3 class="font-cabinet-grotesk font-bold text-lg">Rally with a difference</h3>
              <div class="text-gray-500">Dog meat festival accompanied with rallies across Billiri local government. Last held on the 1st and 2nd January, 2023</div>
            </div>

          </div>

        </div>

        <!-- CTA -->
        <div class="text-center">
          <router-link class="btn inline-flex items-center text-white bg-gray-900 hover:bg-gray-800 group" to="/schedule-call">
            Donate Now
            <span class="tracking-normal text-blue-500 group-hover:translate-x-0.5 transition-transform duration-150 ease-in-out ml-2">
              <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="16" height="8">
                <path d="m10.865.013.747.148c.243.065.481.143.716.235.495.18.97.42 1.415.716.265.192.571.343.858.55.096.064.192.135.288.209l.196.154.192.178c.09.08.175.168.254.262.189.21.33.466.414.747.076.275.073.568-.008.84-.09.27-.236.513-.427.708-.096.1-.198.191-.306.274l-.152.117-.116.074c-.369.252-.75.482-1.14.69-.577.315-1.153.585-1.701.932-.408.262-.803.549-1.182.86-.083.064-.16.136-.247.193a.918.918 0 0 1-.113.072.644.644 0 0 1-.118.016.708.708 0 0 1-.191.01.559.559 0 0 1-.246-.088l-.072-.054a1.481 1.481 0 0 1-.141-.107c-.128-.122-.1-.377.05-.726.036-.08.079-.156.128-.226l.316-.401c.164-.188.336-.372.514-.543.178-.17.356-.342.546-.493.19-.152.394-.265.59-.39.53-.329 1.05-.626 1.552-.93-.159.018-.32.034-.48.04-.511.036-1.026.044-1.546.048a43.432 43.432 0 0 1-2.31-.058l-.005-.02a78.728 78.728 0 0 0-2.292-.148c-.279-.016-.558.01-.837-.006L4.543 3.81l-.977-.046a19.357 19.357 0 0 1-.49-.029 12.6 12.6 0 0 0-1.303.013l-.828.055-.406.021H.335l-.18.008c-.145 0-.208-.15-.102-.356.16-.268.422-.46.723-.531.57-.117 1.144-.205 1.72-.264.287-.026.576-.048.865-.053.29-.004.578.01.865.042.69.065 1.408-.015 2.113-.015.776.003 1.549.02 2.324.04l1.428.039 1.087.039c.359.012.716.02 1.075.013.442-.008.879-.065 1.318-.112a3.672 3.672 0 0 0-.186-.166 9.045 9.045 0 0 0-1.06-.762 9.82 9.82 0 0 0-1.034-.537 5.9 5.9 0 0 1-1.284-.854c-.12-.115-.053-.199.12-.26a1.55 1.55 0 0 1 .738-.083Z" />
              </svg>
            </span>
          </router-link>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
import { ref } from 'vue'
import Modal from '../utils/Modal.vue'

export default {
  name: 'Explainer',
  components: {
    Modal,
  },
  setup() {

    const videoModalOpen = ref(false)

    return {
      videoModalOpen,
    }
  }  
}
</script>