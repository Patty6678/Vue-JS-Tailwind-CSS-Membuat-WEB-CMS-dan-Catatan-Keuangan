<script setup>

import NavbarArtikel from '../components/NavbarArtikel.vue';
import kaki from '../components/Footer.vue';

</script>

<template>
    <div>

        <NavbarArtikel/>
        
    </div>

    <section class="bg-utama dark:bg-gray-900">
        <div class="flex max-w-screen-xl px-4 py-8 mx-auto justify-center  ">                
            <img class="" src="../assets/gambar2.svg" alt="mockup">     
        </div>
   </section>

  <section class=" bg-utama pb-24">
    <div class=" items-center">
      <center><h1 class="bg-utama pt-10 font-semibold tracking-tight leading-none text-3xl	">Rekomendasi Artikel</h1></center>
      
    </div>


    <div class=" md:max-w-screen-xl mx-auto px-4 pt-8 pb-4 justify-center flex items-center ">

      <td class="">
        <tr class="">
          <img class=" w-72 h-36 " src="../assets/Gambar1.png" alt="">
        </tr>
        
        
      </td>

      <td class=" px-4">
          <h5 class=" pt-4 font-semibold tracking-tight leading-none text-gray-600">Metroverse Genesis</h5>
          
          <H1 class="font-bold tracking-light leading-none text-black text-4xl">Artikel A</H1>
          
          <h5>Owned by <b class=" text-yellow-300">BabyKee</b></h5>
          <p class=" py-4">Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.</p>
        </td>

      <td class="">
        <router-link
              to="/artikel/1"
              custom
              v-slot="{ navigate }"
            >
              <button
                @click="navigate"
                role="link"
                class=" mt-24 focus:outline-none text-white bg-yellow-400 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-xl px-10 py-4 mr-2 mb-2 dark:focus:ring-yellow-900"
              >
                <span>Baca</span>
              </button>
            </router-link>
      </td>
    </div>




    <div class=" md:max-w-screen-xl mx-auto px-4 py-4 justify-center flex items-center ">

      <td class="">
        <tr class="">
          <img class=" w-72 h-36 " src="../assets/Gambar1.png" alt="">
        </tr>
        
        
      </td>

      <td class=" px-4">
          <h5 class=" pt-4 font-semibold tracking-tight leading-none text-gray-600">Metroverse Genesis</h5>
          
          <H1 class="font-bold tracking-light leading-none text-black text-4xl">Artikel A</H1>
          
          <h5>Owned by <b class=" text-yellow-300">BabyKee</b></h5>
          <p class=" py-4">Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.</p>
        </td>

      <td class="">
        
        <button type="button" class=" mt-24 focus:outline-none text-white bg-yellow-400 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-xl px-10 py-4 mr-2 mb-2 dark:focus:ring-yellow-900 "> Baca </button>
      </td>
    </div>

    <div class=" md:max-w-screen-xl mx-auto px-4 py-4 justify-center flex items-center ">

      <td class="">
        <tr class="">
          <img class=" w-72 h-36 " src="../assets/Gambar1.png" alt="">
        </tr>
        
        
      </td>

      <td class=" px-4">
          <h5 class=" pt-4 font-semibold tracking-tight leading-none text-gray-600">Metroverse Genesis</h5>
          
          <H1 class="font-bold tracking-light leading-none text-black text-4xl">Artikel A</H1>
          
          <h5>Owned by <b class=" text-yellow-300">BabyKee</b></h5>
          <p class=" py-4">Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.Tersedia artikel dari sumber - sumber terpercaya yang dapat kamu baca untuk meningkatkan wawasan financial.</p>
        </td>

      <td class="">
        <button type="button" class=" mt-24 focus:outline-none text-white bg-yellow-400 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-xl px-10 py-4 mr-2 mb-2 dark:focus:ring-yellow-900 "> Baca </button>
      </td>
    </div>

  </section>

    

   <section>

        <kaki/>
   </section>
    
    
</template>