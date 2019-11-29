<template>
<footer class="app-footer is-top">
  <div class="hero-body">
    <div class="container">
      <div class="columns">
        <div class="column is-6 is-5-widescreen">
          <div class="summary">

            <router-link :to="$i18nRoute({ name: 'home'})" class="brand">
              <div class="brand-icon"> <img alt="Bedtime Stories" role="presentation" src="@/assets/img/app-icon.png">
              </div>
              <div class="brand-content">
                <div class="brand-title"> {{ $t("brand.title") }} </div>
                <div class="brand-subtitle"> {{ $t("brand.subtitle") }}</div>
              </div>
            </router-link>
            <hr class="spacer is-2">
            <p class="is-size-6"> {{ $t("brand.description") }}</p>
            <hr class="spacer is-2">
            <a href="http://www.google.com" class="app-store-badge" target="_blank">
              <img role="presentation" src="@/assets/svg/icons/webapp.svg">
            </a>
            <a href="http://www.google.com" class="app-store-badge" target="_blank">
              <img role="presentation" src="@/assets/svg/icons/ios.svg">
            </a>
            <a href="http://www.google.com" class="app-store-badge" target="_blank">
              <img role="presentation" src="@/assets/svg/icons/android.svg">
            </a>
            <hr class="spacer is-1">
            <p class="menu-label is-size-6">{{ $t("nav.follow-us") }}</p>
            <div class="field is-grouped">
              <div class="control"><a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="spectrum" />
                </a> </div>
              <div class="control"><a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="medium" />
                </a> </div>
              <div class="control"><a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="twitter" />
                </a> </div>
              <div class="control"> <a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="youtube" />
                </a> </div>
              <div class="control"> <a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="spotify" />
                </a> </div>
              <div class="control"> <a href="http://www.google.com" target="_blank" class="button is-white has-shadow">
                  <base-icon name="linkedin" />
                </a> </div>
            </div>
          </div>
        </div>
        <hr class="spacer is-2">
        <div class="column is-7 is-6-widescreen is-offset-1-widescreen">
          <div class="columns">
            <div class="column is-4">
              <div class="menu">
                <p class="menu-label">{{ $t("nav.category-product") }}</p>
                <ul class="menu-list">
                  <li>
                    <router-link :to="$i18nRoute({ name: 'home'})" exact>{{ $t("nav.home") }}</router-link>
                  </li>
                  <li>
                    <router-link :to="$i18nRoute({ name: 'features'})">{{ $t("nav.features") }}</router-link>
                  </li>
                  <li>
                    <router-link :to="$i18nRoute({ name: 'updates'})">{{ $t("nav.updates") }}</router-link>
                  </li>
                  <li>
                    <router-link :to="$i18nRoute({ name: 'security'})">{{ $t("nav.security") }}</router-link>
                  </li>
                  <li>
                    <router-link :to="$i18nRoute({ name: 'pricing'})">{{ $t("nav.pricing") }}</router-link>
                  </li>
                </ul>
              </div>
            </div>
            <div class="column is-4">
              <div class="menu">
                <p class="menu-label">{{ $t("nav.category-resources") }}</p>
                <ul class="menu-list">
                  <li><a href="/external_medium" target="_blank">{{ $t("nav.news") }}</a></li>
                  <li><a href="/external_spectrum">{{ $t("nav.community") }}</a></li>
                  <li><a href="/external_trello">{{ $t("nav.roadmap") }}</a></li>
                  <li><a href="/external_documentation">{{ $t("nav.help") }}</a></li>

                </ul>
              </div>
            </div>
            <div class="column is-4">
              <div class="menu">
                <p class="menu-label">{{ $t("nav.category-company") }}</p>
                <ul class="menu-list">
                  <li>
                    <router-link :to="$i18nRoute({ name: 'about'})">{{ $t("nav.about") }}</router-link>
                  </li>
                  <li>
                    <router-link :to="$i18nRoute({ name: 'values'})">{{ $t("nav.values") }}</router-link>
                  </li>
                  <li><a href="/external_linkedin" target="_blank">{{ $t("nav.jobs") }}</a></li>
                  <li><a href="mailto:email@email.com?subject=%F0%9F%91%8B%20Hello&body=If%20you%20need%20help%20you%20can%20also%20visit%20our%20community%20at%20www.google.com" target="_blank">{{ $t("nav.contact") }}</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container bottom-links">
      <div class="columns is-vcentered">
        <div class="column is-6">
          <nav class="menu-hor has-space-separator is-left">
            <ul class="menu-list-hor">
              <li>
                <router-link to="privacy">{{ $t("nav.privacy") }}</router-link>
              </li>
              <li>
                <router-link to="terms">{{ $t("nav.terms") }}</router-link>
              </li>
              <li>
                <router-link to="cookies">{{ $t("nav.cookies") }}</router-link>
              </li>
            </ul>
          </nav>
        </div>
        <div class="column colophon has-text-right is-hidden-mobile">
          {{ $t("brand.colophon") }}
        </div>
        <div class="column colophon has-text-left is-hidden-tablet">
          {{ $t("brand.colophon") }}
        </div>
        <div class="column is-1 lang-select">
          <LangSwitch />
        </div>
      </div>
    </div>
  </div>
</footer>
</template>

<script>
import BaseIcon from '@/components/atoms/BaseIcon.vue'
import LangSwitch from '@/components/atoms/LangSwitch'

export default {
  name: `Footer`,
  components: {
    BaseIcon,
    LangSwitch
  }
}
</script>
