<template>
<footer class="app-footer is-medium">
  <div class="hero-body">
    <div class="container">
      <div class="columns">
        <div class="column is-6 is-5-widescreen">
          <div class="summary"> <a class="brand" href="/">
              <div class="brand-icon"> <img alt="Bedtime Stories" role="presentation" src="@/assets/img/app-icon.png">
              </div>
              <div class="brand-content">
                <div class="brand-title"> Bedtime Stories </div>
                <div class="brand-subtitle"> Exciting tales for young &amp; old </div>
              </div>
            </a>
            <hr class="spacer is-2">
            <p class="is-size-6"> The storytelling app for families - read diverse &amp; empowering stories or tell them in your own words. </p>
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
            <p class="menu-label is-size-6">Follow Us</p>
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
                <p class="menu-label">Product</p>
                <ul class="menu-list">
                  <li>
                    <router-link exact to="/">Home</router-link>
                  </li>
                  <li>
                    <router-link to="features">Features</router-link>
                  </li>
                  <li>
                    <router-link to="updates">Updates</router-link>
                  </li>
                  <li>
                    <router-link to="pricing">Pricing</router-link>
                  </li>
                  <li> <a href="/external_spectrum">Community ↗</a> </li>
                  <li> <a href="/external_trello">Roadmap ↗</a> </li>
                </ul>
              </div>
            </div>
            <div class="column is-4">
              <div class="menu">
                <p class="menu-label">Company</p>
                <ul class="menu-list">
                  <li>
                    <router-link to="about">About</router-link>
                  </li>
                  <li> <a href="external_medium" target="_blank">News ↗</a> </li>
                  <li> <a href="external_linkedin" target="_blank">Jobs ↗</a> </li>
                  <li> <a href="mailto:email@email.com?subject=%F0%9F%91%8B%20Hello&body=If%20you%20need%20help%20you%20can%20also%20visit%20our%20community%20at%20www.google.com" target="_blank">Contact ↗</a> </li>
                </ul>
              </div>
            </div>
            <div class="column is-4">
              <div class="menu">
                <p class="menu-label">Legal</p>
                <ul class="menu-list">
                  <li>
                    <router-link to="security">Security</router-link>
                  </li>
                  <li>
                    <router-link to="privacy">Privacy</router-link>
                  </li>
                  <li>
                    <router-link to="terms">Terms</router-link>
                  </li>
                  <li>
                    <router-link to="cookies">Cookies</router-link>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="has-text-left">
      <p>Made by hand in over 75 cities around the world. © 2019 Help Scout </p>
    </div>
  </div>
</footer>
</template>

<script>
import BaseIcon from '@/components/atoms/BaseIcon.vue'

export default {
  name: `FooterAlt`,
  components: {
    BaseIcon
  }
}
</script>
