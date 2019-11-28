<template>
<section class="hero section is-hero is-medium is-primary is-bold">
  <div class="container">
    <div class="columns is-vcentered">
      <div class="column is-5-fullhd is-offset-1-fullhd">
        <div class="section-header">
          <h1 class="title is-spaced"> {{ $t("hero.title") }}
          </h1>
          <h2 class="subtitle is-4"> {{ $t("hero.subtitle") }} </h2>
          <div class="field is-grouped">
            <div class="control"> <a class="button is-primary is-medium" href="#platform">{{ $t("hero.btn-primary") }}</a> </div>
            <div class="control"> <a class="button is-light is-medium" href="/library">{{ $t("hero.btn-secondary") }}</a> </div>
          </div>
          <hr class="spacer is-1-5">
          <a class="has-tint has-text-weight-semibold" href="http://www.parents-choice.org/product.cfm?product_id=35555" target="_blank"><i class="icon icon-award"></i><span>Parents' Choice Approved App</span></a>
        </div>
      </div>
      <div class="column is-6">
        <div class="section-media"> <img role="presentation" src="@/assets/img/header.jpg">
          <p> <small><a href="/library/karlotta-the-knight"><u>Karlotta the Knight</u></a> with her squire and steed.</small> </p>
        </div>
      </div>
    </div>
  </div>
</section>
</template>
