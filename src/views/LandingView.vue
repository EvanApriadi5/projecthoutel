<template>
   <div class="LandingView">
<!-- // call component // -->
<header-comp/>
<banner-comp/>
<hotel-rec/>
<hotel-rec2/>
<iklan-comp/>
<tagline/>
<footer-comp/>


</div>

</template>

<script>
// import komponen//
import HeaderComp from '@/components/HeaderComp.vue'
import BannerComp from '@/components/BannerComp.vue';
import HotelRec from '@/components/HotelRec.vue';
import HotelRec2 from '@/components/HotelRec2.vue';
import IklanComp from '@/components/IklanComp.vue';
import Tagline from '@/components/Tagline.vue';
import FooterComp from '@/components/FooterComp.vue';






export default {
  name: 'LandingView',
  // Regist component //
   components: { HeaderComp, BannerComp, HotelRec, HotelRec2, IklanComp, Tagline, FooterComp, },
  };

   
</script>