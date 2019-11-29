<template>
<section class="hero section is-hero is-medium is-primary is-bold">
  <div class="container">
    <div class="columns is-centered">
      <div class="column is-half is-offset-1-fullhd">
        <div class="section-header">
          <h1 class="title is-spaced"> {{ $t("c-hero.title") }}</h1>
          <h2 class="subtitle is-4"> {{ $t("c-hero.subtitle") }}</h2>
          <div class="field is-grouped">
            <div class="control"> <a class="button is-warning is-medium" href="#courses">{{ $t("c-hero.btn-primary") }}</a> </div>
            <div class="control"> <a class="button is-light is-medium" href="#courses">{{ $t("c-hero.btn-secondary") }}</a> </div>
          </div>
        </div>
      </div>
      <div class="column is-half">
        <div class="section-media"> <img class="full-width" role="presentation" src="@/assets/svg/illos/school.svg">
          <p> <small>{{ $t("c-hero.img-caption") }}</small> </p>
        </div>
      </div>
    </div>
  </div>
</section>
</template>
