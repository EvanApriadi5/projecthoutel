<template>
   <div class="DetailView">
<!-- // call component // -->
<header-comp/>
<detail-comp/>
<footer-comp/>




</div>

</template>

<script>
// import komponen//
import HeaderComp from '@/components/HeaderComp.vue'
import DetailComp from '@/components/DetailComp.vue';
import FooterComp from '@/components/FooterComp.vue';








export default {
  name: 'DetailView',
  // Regist component //
   components: { HeaderComp, DetailComp, FooterComp },
  };

   
</script>