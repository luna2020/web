<template>
<layout-default>
  <section class="section hero has-background is-large">
    <div class="container">
      <div class="has-text-centered">
        <div class="columns is-mobile is-centered">
          <div class="column is-half-mobile is-one-third-tablet is-one-third-desktop is-one-third-widescreen is-one-third-fullhd">
            <img class="is-flex image is-centered" src="@/assets/img/not-found-3.png">
          </div>
        </div>
        <h1 class="title is-1 is-spaced"> Page not found </h1>
        <h2 class="subtitle is-5"> How did you even end up here? </h2>
        <hr class="spacer is-1">
        <router-link to="/" class="button is-primary is-medium">Bring me back</router-link>
      </div>
    </div>
  </section>
</layout-default>
</template>

<script>
import LayoutDefault from '@/layouts/LayoutDefault.vue'

export default {
  name: 'NotFound',
  components: {
    LayoutDefault
  }
}
</script>
