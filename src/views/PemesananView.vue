<template>
   <div class="PemesananView">
<header-comp/>
<pemesanan-comp/>
<footer-comp/>

</div>

</template>

<script>
import HeaderComp from '@/components/HeaderComp.vue'
import FooterComp from '@/components/FooterComp.vue'
import PemesananComp from '@/components/PemesananComp.vue';



export default {
  name: 'PemesananView',
  // Regist component //
   components: { HeaderComp, FooterComp, PemesananComp},
  };
</script>