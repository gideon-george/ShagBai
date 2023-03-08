<template>
  <main class="flex">

    <!-- Content -->
    <div class="min-h-screen w-full lg:w-1/2">

      <div class="h-full">

        <div class="h-full w-full max-w-md px-6 mx-auto flex flex-col after:mt-auto after:flex-1">

          <!-- Site header -->
          <header class="flex-1 flex mb-auto">
            <div class="flex items-center justify-between h-16 md:h-20">
              <!-- Logo -->
              <router-link class="block group" to="/" aria-label="Cruip">
                <svg width="30" height="30" xmlns="http://www.w3.org/2000/svg">
                  <path class="fill-blue-600 group-hover:fill-blue-500 transform duration-150 ease-in-out" d="M12 6v24C5.373 30 0 24.627 0 18S5.373 6 12 6Z" />
                  <path class="fill-sky-400 group-hover:fill-sky-300 transform duration-150 ease-in-out" d="M10.807 6.059A10.003 10.003 0 0 1 20 0c5.523 0 10 4.477 10 10 0 4.123-2.496 7.664-6.059 9.193.04-.392.059-.79.059-1.193 0-6.627-5.373-12-12-12-.403 0-.8.02-1.193.059Z" />
                </svg>
              </router-link>
            </div>
          </header>

          <div class="flex-1 py-8">

            <div class="bg-gray-100 p-6 rounded-lg">
  <h2 class="text-2xl font-bold mb-4">Help Free Our Captive Brothers</h2>
  <p class="mb-4">Dear brothers and sisters,</p>
  <p class="mb-4">We write to you today with a heavy heart to request your help and support for our brothers who have been held captive due to the Mai Tangale crisis. These individuals have been separated from their families and need our assistance.</p>
  <p class="mb-4">We are therefore calling on you to make a donation to Maikwada Maikenti's bank account at Zenith Bank with account number 2004137016. All donations made to this account will be used to support them in the best possible way.</p>
  <p class="mb-4">Your contribution, no matter how small, will make a significant difference in the lives of these individuals and their families. By donating, you will be showing your support and solidarity with those who are suffering, and will be helping to alleviate their burden in a time of crisis.</p>
  <p class="mb-4">We urge you to act now and make a donation to Maikwada Maikenti's bank account at Zenith Bank with account number 2004137016. Your generosity will be greatly appreciated and will go a long way in helping those who are in desperate need of our support.</p>
  <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-full inline-block">Donate Now</button>
  <p class="mt-4">Thank you for your consideration and support.</p>
  <p class="mt-4">Sincerely,</p>
  <p>The ShagBai Team</p>
</div>

          

          </div>

        </div>

      </div>

    </div>

    <!-- Right side -->
    <div class="fixed right-0 top-0 bottom-0 hidden lg:block lg:w-1/2 overflow-hidden" aria-hidden="true">

      <!-- Bg -->
      <div class="absolute inset-0 bg-blue-600 pointer-events-none -z-10"></div>

      <!-- Illustration -->
      <div class="absolute left-1/2 -translate-x-1/4 pointer-events-none -z-10">
        <!-- Had to place the SVG in the public folder, and here is why:
          Ref: https://github.com/vitejs/vite/issues/7062 -->
        <object type="image/svg+xml" data="/hero-illustration.svg" width="1440" height="1214"></object>
      </div>

      <!-- Quotes -->
      <div class="absolute inset-0 flex flex-col justify-center space-y-3">
        <div class="flex flex-nowrap space-x-3 mx-auto -translate-x-1/4">
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-60 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-80 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-nowrap space-x-3 mx-auto">
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-80 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-70 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-nowrap space-x-3 mx-auto translate-x-1/4">
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-40 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
          <!-- Card -->
          <div class="w-72 shrink-0 p-4 bg-white rounded opacity-25 hover:opacity-100 transition duration-150 ease-in-out">
            <div class="flex items-center space-x-3">
              <div class="shrink-0">
                <img class="rounded-full" src="" width="44" height="44" alt="" />
              </div>
              <div>
                <div class="font-cabinet-grotesk text-gray-900 font-bold"></div>
                <div class="font-medium text-sm text-gray-600"></div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>

  </main>
</template>

<script>
export default {
  name: 'ScheduleCall',
}
</script>