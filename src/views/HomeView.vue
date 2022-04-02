<template>
  <div class="home">
    <HeaderTokovue />
    <Hero-tokovue />
    <BannerTokovue />
    <InstaTokovue />
    <PartnerTokovue />
    <FooterTokovue />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderTokovue from "@/components/HeaderTokovue.vue";
import HeroTokovue from "@/components/HeroTokovue.vue";
import BannerTokovue from "@/components/BannerTokovue.vue";
import InstaTokovue from "@/components/InstaTokovue.vue";
import PartnerTokovue from "@/components/PartnerTokovue.vue";
import FooterTokovue from "@/components/FooterTokovue.vue";

export default {
  name: "HomeView",
  components: {
    HeaderTokovue,
    HeroTokovue,
    BannerTokovue,
    InstaTokovue,
    PartnerTokovue,
    FooterTokovue,
  },
};
</script>
