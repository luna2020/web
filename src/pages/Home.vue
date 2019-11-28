<template>
<layout-default>
  <HeroHome />
</layout-default>
</template>

<script>
import HeroHome from '@/components/HeroHome.vue'
import LayoutDefault from '@/layouts/LayoutDefault.vue'


export default {
  name: 'Home',
  components: {
    HeroHome,
    LayoutDefault
  }
}
</script>
