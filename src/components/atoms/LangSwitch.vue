<template>
<div class="field">
  <div class="control">
   <div class="select is-lang">
  <select class="select is-lang" name="language" @change="changeLanguage">
    <option
      v-for="entry in supportedLanguages"
      :key="entry"
      :selected="isCurrentLanguage(entry)"
      :class="{ 'is-selected': isCurrentLanguage(entry) }"
      :value="entry"
    >
      {{entry}}
    </option>
  </select>
    </div>

    
  </div>
</div>
</template>
<script>
import { Trans } from '@/plugins/i18n/Translation'

export default {
  computed: {
    supportedLanguages () {
      return Trans.supportedLanguages
    },
    currentLanguage () {
      return Trans.currentLanguage
    }
  },
  methods: {
    changeLanguage (e) {
      const lang = e.target.value
      const to = this.$router.resolve({ params: { lang } })
      return Trans.changeLanguage(lang).then(() => {
        this.$router.push(to.location)
      })
    },
    isCurrentLanguage (lang) {
      return lang === this.currentLanguage
    }
  }
}
</script>

