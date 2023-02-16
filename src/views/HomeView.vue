<template>
  <div class="home">
    <HeaderStore />
    <HeroStore />
    <ItemStore />
    <InstaStore />
    <LogoStore />
    <FooterStore />
  </div>
</template>

<script>
import HeaderStore from "@/components/HeaderStore.vue";
import HeroStore from "@/components/HeroStore.vue";
import ItemStore from "@/components/ItemStore.vue";
import InstaStore from "@/components/InstaStore.vue";
import LogoStore from "@/components/LogoStore.vue";
import FooterStore from "@/components/FooterStore.vue";

export default {
  components: {
    HeaderStore,
    HeroStore,
    ItemStore,
    InstaStore,
    LogoStore,
    FooterStore
  }
};
</script>
