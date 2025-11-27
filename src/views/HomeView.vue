<template>
  <div>
    <MyNavbar/>
  </div>

  <div class=" lg:pl-50 flex flex-col md:flex-row items-center justify-center backGroundMain p-6 md:p-10 gap-6 lg:mt-40">


    <div class="flex shrink-0">
      <Image
        class="rounded-full object-cover imgMain w-100"
        :src="logoFinale"
        alt="Icona"
        layout="constrained"
        :width="400"
        :height="400"
      />
    </div>


    <div class="flex flex-col text-center md:text-left lg:ml-10 lg:pr-80">
      <h1 class="text-3xl lg:text-4xl font-extrabold textTit roboto-slab">PROGETTO MEUCCI</h1>
      <h2 class="text-2xl font-bold textSub roboto-slab">"La scuola che vogliamo, la costruiamo insieme"</h2>
      <p class="lg:text-xl  text-lg  mt-2 textTit roboto-slab">
        La nostra lista si impegna a migliorare la scuola attraverso progetti concreti e inclusivi, pensati per valorizzare ogni studente.
        <br>Vogliamo rendere l’ambiente scolastico più accogliente,
        sicuro e stimolante, promuovendo attività che favoriscano collaborazione, partecipazione e benessere.
        <br>Il nostro obiettivo è costruire una comunità scolastica più moderna,
        <br>attenta alle esigenze di tutti e capace di offrire nuove opportunità di crescita.
      </p>
    </div>


  </div>
  <ChiSiamo/>
  <OurProjects/>
  <MyFooter/>
</template>

<script setup>
import { Image } from '@unpic/vue';
import MyFooter from '@/components/MyFooter.vue';
import MyNavbar from '@/components/MyNavbar.vue';
import ChiSiamo from './ChiSiamo.vue';
import OurProjects from './OurProjects.vue';
import logoFinale from '@/assets/logoFinale.png';
</script>

