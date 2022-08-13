<template>
   <div class="listView">
<!-- // call component // -->
<header-comp/>
<Find-hotel/>
<footer-comp/>


</div>

</template>

<script>
// import komponen//
import HeaderComp from '@/components/HeaderComp.vue'
import FindHotel from '@/components/FindHotel.vue'
import FooterComp from '@/components/FooterComp.vue';






export default {
  name: 'listView',
  // Regist component //
   components: { HeaderComp, FindHotel, FooterComp},
  };

   
</script>