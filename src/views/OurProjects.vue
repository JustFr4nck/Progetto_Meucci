<template>
  <div class="pb-30">

    <div class="lg:pt-60 pt-20 flex flex-row text-center justify-center pb-10">
      <h1 class="text-3xl lg:text-4xl font-extrabold textSub roboto-slab">Projects</h1>
    </div>


    <div class="md:hidden flex justify-center">
      <div class="carousel rounded-box w-80">
        <div class=" flex flex-col items-center carousel-item w-full bg-caru">
          <img src="../assets/connected.png" class=" rounded-xl w-45 h-45 mt-5" />
          <h1 class="textClear">...</h1>
        </div>
        <div class="flex flex-col items-center carousel-item w-full bg-caru">
          <img src="../assets/giovaniWannabe.jpeg" class="rounded-xl w-45 h-45 mt-5" />
          <h1 class="textSub text-2xl font-bold mt-2 text-center">Assemblee con <br> "Giovani Wannabe"</h1>
          <h1 class="textClear text-md text-center ml-4 mr-4 mb-4">Nonostante le difficoltà, noi ci stiamo battendo per riportare le assemblee! Grazie all'aiuto di <a href="https://www.instagram.com/giovani.wannabe_?igsh=MTRkdzlmd3Boc24xOQ==">@giovani.wannabe_</a>, vogliamo dare voce agli studenti e renderli protagonisti della vita scolastica.</h1>
        </div>
        <div class="carousel-item w-full">
          <img src="https://img.daisyui.com/images/stock/photo-1565098772267-60af42b81ef2.webp" class="w-full" />
        </div>
      </div>
    </div>


    <div class="hidden md:flex justify-center gap-20 px-10">
      <div>
        <img src="../assets/connected.png"
          class="rounded-2xl object-cover shadow-lg w-50 h-50" />
      </div>
      <div><img src="https://img.daisyui.com/images/stock/photo-1565098772267-60af42b81ef2.webp"
          class="rounded-2xl w-60 object-cover shadow-lg" /></div>
      <div><img src="https://img.daisyui.com/images/stock/photo-1565098772267-60af42b81ef2.webp"
          class="rounded-2xl w-60 object-cover shadow-lg" /></div>
    </div>

  </div>
</template>


<style scoped>

.bg-caru{

  background-color: #042C54;
}

.textClear{

  color: #FFFCF2;
}
</style>
