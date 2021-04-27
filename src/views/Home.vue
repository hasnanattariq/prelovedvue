<template>
  <div class="home">
    <HeaderPreloved />
    <HeroPreloved />
    <BannerPreloved />
    <InstaPreloved />
    <PartnerPreloved />
    <FooterPreloved />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderPreloved from '@/components/HeaderPreloved.vue'
import HeroPreloved from '@/components/HeroPreloved.vue'
import BannerPreloved from '@/components/BannerPreloved.vue'
import InstaPreloved from '@/components/InstaPreloved.vue'
import PartnerPreloved from '@/components/PartnerPreloved.vue'
import FooterPreloved from '@/components/FooterPreloved.vue'

export default {
  name: 'Home',
  components: {
    HeaderPreloved,
    HeroPreloved,
    BannerPreloved,
    InstaPreloved,
    PartnerPreloved,
    FooterPreloved
  }
}
</script>
