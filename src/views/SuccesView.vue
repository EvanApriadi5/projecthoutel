<template>
  <div class="SuccesView">
    <header-comp/>
    <sukses-comp/>
    <footer-comp/>
  </div>
</template>

<script>
import HeaderComp from "@/components/HeaderComp.vue";
import SuksesComp from "@/components/SuksesComp.vue";
import FooterComp from "@/components/FooterComp.vue";

export default {
  components: { HeaderComp, SuksesComp, FooterComp },
  name: "SuccesView",
};
</script>