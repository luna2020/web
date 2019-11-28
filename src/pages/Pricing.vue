<template>
<layout-default>
  <section class="section is-contact is-top has-background">
  <div class="container">
    <div class="has-text-centered">
      <h2 class="title is-1 is-spaced"> Don't be shy, say hi! </h2>
      <p class="subtitle is-5"> We might deal with trolls, werewolfs and huge dogs, but we don’t bite. </p>
    </div>
  </div>
</section>
  <SectionCards />
  <section class="section has-background">
    <div class="container">
      <p> By using our website you consent to the collection, processing and use of data as described below. Our website can be visited without registration. This data such as pages called or name of the retrieved file, date and time are stored on the server for statistical purposes, without this data are directly related to your person. Personal data, in particular name, address or e-mail address are collected as far as possible on a voluntary basis. Without your consent, the data will not be passed on to third parties. </p>
    </div>
    <hr class="spacer is-4">
  </section>
</layout-default>
</template>

<script>
import LayoutDefault from '@/layouts/LayoutDefault.vue'
import SectionCards from '@/components/SectionCards.vue'

export default {
  name: 'Pricing',
  components: {
    SectionCards,
    LayoutDefault
  }
}
</script>
