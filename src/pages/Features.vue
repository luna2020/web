<template>
<layout-default>
  <Hero class="is-danger is-bold" />
  <TabsVertical />
  <SectionFeatures3 />
  <SectionLeftImg />
  <SectionRightImg />
  <SectionCenter />
</layout-default>
</template>

<script>
import Hero from '@/components/Hero.vue'

import SectionCenter from '@/components/SectionCenter.vue'
import SectionFeatures3 from '@/components/SectionFeatures3.vue'
import SectionLeftImg from '@/components/SectionLeftImg.vue'
import SectionRightImg from '@/components/SectionRightImg.vue'
import TabsVertical from '@/components/TabsVertical.vue'
import LayoutDefault from '@/layouts/LayoutDefault.vue'

export default {
  name: 'Features',
  components: {
    Hero,
    SectionCenter,
    SectionFeatures3,
    SectionLeftImg,
    SectionRightImg,
    TabsVertical,
    LayoutDefault
  }
}
</script>
