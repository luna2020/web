<template>
<section>
  <div class="container">
    <b-tabs position="is-centered" class="block">
      <b-tab-item label="Pictures" icon="google-photos">
        <div class="container">
          <div class="section-header has-text-centered">
            <h2 class="title is-1 is-spaced"> {{ $t("c-tabs-horizontal.title") }} </h2>
            <p class="subtitle is-4"> {{ $t("c-tabs-horizontal.subtitle") }} </p>
          </div>
        </div>
      </b-tab-item>
      <b-tab-item label="Music" icon="library-music">
      </b-tab-item>
      <b-tab-item label="Videos" icon="video">
      </b-tab-item>
    </b-tabs>
  </div>
</section>
</template>
