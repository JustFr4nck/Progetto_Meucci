<template>
  <div class="flex flex-col-reverse md:flex-row items-center justify-center gap-10 px-6 md:px-20 pt-20 lg:pt-60 pb-20">

    <div class="w-full md:w-1/2 md:text-left text-center">
      <h1 class="text-3xl lg:text-4xl font-extrabold textSub roboto-slab">Chi siamo</h1>
      <p class="textTit lg:text-xl text-lg leading-relaxed roboto-slab mt-4">
        Siamo due studenti di quinta che tengono davvero alla nostra scuola.
        Ci candidiamo perché vogliamo lasciare qualcosa di positivo prima di andarcene:
        piccole cose concrete che possano migliorare la vita di tutti i giorni.
        Vogliamo ascoltare le idee degli altri, capire cosa serve davvero e impegnarci
        per farlo succedere nel modo più pratico possibile.
      </p>
    </div>

    <div class="w-full md:w-1/2 flex justify-center md:justify-end">
      <Image
        :src="velaMare"
        alt="Foto"
        class="rounded-2xl object-cover w-full max-w-md shadow-lg lg:mr-30"
        layout="constrained"
        :width="800"
        :height="1066"
      />
    </div>

  </div>
</template>

<script setup>
import { Image } from '@unpic/vue';
import velaMare from '@/assets/velaMare.jpeg';
</script>

