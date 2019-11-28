<template>
<header class="app-header">
  <nav class="navbar">
    <div class="container">
      <div class="navbar-brand">
        <div class="navbar-item">
              <router-link :to="$i18nRoute({ name: 'home'})" exact class="brand">

            <div class="brand-icon"> <img alt="Bedtime Stories" role="presentation" src="@/assets/img/app-icon.png"> </div>
            <div class="brand-content">
              <div class="brand-title is-hidden-mobile "> Bedtime Stories </div>
              <div class="brand-subtitle is-hidden-mobile"> Exciting tales for young &amp; old </div>
            </div>
          </router-link>
        </div>
        <div class="mobile-menu-simple is-marginless is-hidden-desktop">
         <router-link :to="$i18nRoute({ name: 'features'})" class="navbar-item">Features</router-link>
          <router-link :to="$i18nRoute({ name: 'updates'})" class="navbar-item ">Updates</router-link>
          <span class="is-invisible">|</span>
          <a href="/login" class="navbar-item button is-light">🚀</a>
        </div>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <router-link :to="$i18nRoute({ name: 'home'})" exact class="navbar-item">Home</router-link>
          <router-link :to="$i18nRoute({ name: 'features'})" class="navbar-item">Features</router-link>
          <router-link :to="$i18nRoute({ name: 'updates'})" class="navbar-item ">Updates<span class="tag is-warning is-micro is-uppercase">New</span></router-link>
          <div class="navbar-item">
            <a href="/login" class="button is-light">🚀 Let's go</a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</header>
</template>