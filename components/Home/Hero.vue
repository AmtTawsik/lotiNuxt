<template>
  <div class="pt-24 gradient text-white">
    <div class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center justify-center">
      <!--Left Col-->
      <div class="flex flex-col w-full md:w-3/5 justify-center items-start text-center md:text-left">
        <p class="uppercase tracking-loose w-full">What business are you?</p>
        <h1 class="my-4 text-5xl font-bold ">
          Main Hero Message to sell yourself!
        </h1>
        <p class="leading-normal text-2xl mb-8">
          Sub-hero message, not too long and not too short. Make it just right!
        </p>
        <button
          class="mx-auto lg:mx-0 hover:underline bg-white text-gray-800 font-bold rounded-full my-6 py-4 px-8 shadow-lg focus:outline-none focus:shadow-outline transform transition hover:scale-105 duration-300 ease-in-out">
          Subscribe
        </button>
      </div>
      <!--Right Col-->
      <div class="w-full md:w-2/5 text-center">
        <!-- <client-only>
          <Vue3Lottie animationLink="https://lottie.host/1ebf0611-6776-458c-b8b0-57f61f75f838/2US1yrdzKR.json"
            :height="300" background="transparent" speed="1" />
        </client-only> -->
        <iframe height="300px" width="100%"
          src="https://lottie.host/?file=6eb1836e-bd1f-4eca-8e63-0ad92ac08b47/9aKpDSdgnc.json"></iframe>
      </div>
    </div>
  </div>
  <div class="relative -mt-8">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <!-- Define the linear gradient in the <defs> section -->
      <defs>
        <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#37C6AB" />
          <stop offset="100%" stop-color="#517CDA" />
        </linearGradient>
      </defs>
      <path fill="url(#gradient)" fill-opacity="1"
        d="M0,160L60,170.7C120,181,240,203,360,186.7C480,171,600,117,720,101.3C840,85,960,107,1080,144C1200,181,1320,235,1380,261.3L1440,288L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z">
      </path>
    </svg>
  </div>
  <section class="bg-white border-b pb-8">
    <div class="container max-w-5xl mx-auto m-8">
      <h2 class="w-full my-2 text-5xl font-bold  text-center text-gray-800">
        Title
      </h2>
      <div class="w-full mb-4">
        <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
      </div>
      <div class="flex flex-wrap">
        <div class="w-5/6 sm:w-1/2 mx-auto">
          <h3 class="text-3xl text-gray-800 font-bold leading-none mb-3 items-center">
            Lorem ipsum dolor sit amet
          </h3>
          <p class="text-gray-600 mb-8">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore corrupti dolore ex accusantium
            aut sequi voluptatem veritatis placeat porro ad ratione excepturi modi, culpa praesentium.
            Officiis earum natus porro nulla facilis aliquid, fuga illum officia similique qui minus minima,
            eaque magni ullam totam ratione reprehenderit laborum facere deserunt rem autem cumque tenetur?
            Culpa illum, praesentium at molestias sunt dicta! Tempora, odio. Recusandae optio quo
            consectetur, asperiores, repellat suscipit placeat corporis aut voluptatibus vitae quas
            excepturi, magnam hic cum aliquid iusto.
            <br />
            <br />
          </p>
        </div>
        <div class="w-full sm:w-1/2 p-6">
          <!-- <client-only>
            <Vue3Lottie animationLink="https://lottie.host/1ebf0611-6776-458c-b8b0-57f61f75f838/2US1yrdzKR.json"
              :height="300" background="transparent" speed="1" />
          </client-only> -->
          <iframe height="100%" width="100%"
            src="https://lottie.host/?file=6eb1836e-bd1f-4eca-8e63-0ad92ac08b47/9aKpDSdgnc.json"></iframe>
        </div>
      </div>
      <div class="flex flex-wrap flex-col-reverse sm:flex-row">
        <div class="w-full sm:w-1/2 p-6 mt-6">
          <!-- <client-only>
            <Vue3Lottie animationLink="https://lottie.host/3505cdd8-4eb4-4ca7-a093-3dd446d9198e/VmwGCbchNY.json"
              :height="300" background="transparent" speed="1" />
          </client-only> -->
          <iframe height="100%" width="100%"
            src="https://lottie.host/?file=5802970c-60b6-49ba-9a23-c1fd57236f29/juJ3HAy9Yx.json"></iframe>
        </div>
        <div class="w-full sm:w-1/2 p-6 mx-auto">
          <div class="align-middle">
            <h3 class="text-3xl text-gray-800 font-bold leading-none mb-3 items-center">
              Lorem ipsum dolor sit amet
            </h3>
            <p class="text-gray-600 mb-8">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sunt illo esse maiores molestiae
              nihil molestias fuga, optio asperiores ducimus quis dolorum similique obcaecati totam
              possimus ea sint voluptates velit cumque reprehenderit assumenda illum eveniet? Quaerat eum
              ea temporibus facere autem quasi reiciendis fuga, distinctio nam, fugiat repellat recusandae
              assumenda dolorem minus omnis beatae exercitationem harum dolores nemo natus doloremque
              saepe? Excepturi quo vel voluptate, consectetur at eveniet. Mollitia numquam dicta
              temporibus natus dolore quo sed, ea autem sit, libero pariatur!
              <br />
              <br />
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
</script>

<style scoped>
.gradient {
  background: linear-gradient(90deg, #37C6AB 0%, #517CDA 100%);
}
</style>