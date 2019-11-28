<template>
<layout-default>
  <SectionGrid class="is-medium has-background"/>
  <section class="section is-medium">
    <div class="container">
      <div class="columns">
        <div class="column is-offset-3 is-6">
          <h1 class="title is-1 is-spaced"> Pricing<span class="spacer is-horizontal is-1"></span><span class="tag is-primary">Website</span> </h1>
          <h2 class="subtitle is-5"> Last Update: November 14, 2018 </h2>
          <div class="content is-medium">
            <p> By using our website you consent to the collection, processing and use of data as described below. Our website can be visited without registration. This data such as pages called or name of the retrieved file, date and time are stored on the server for statistical purposes, without this data are directly related to your person. Personal data, in particular name, address or e-mail address are collected as far as possible on a voluntary basis. Without your consent, the data will not be passed on to third parties. </p>
            <h2> Web &amp; Social Media </h2>
            <h3> Contacting Us </h3>
            <p> If you contact us by means of a form on the website or by e-mail, your data will be stored for a period of 12 months in order to process the request and in case of follow-up questions. We will not share this information without your consent. </p>
            <h3> Cookies </h3>
            <p> Our website uses so-called cookies. These are small text files that are stored on your device using the browser and do net present any harm. We use cookies to make our offer user-friendly. Some cookies remain stored on your device until you delete them. They allow us to recognize your browser on your next visit. If you object to this, you can set up your browser so that it informs you about the setting of cookies and you allow this only in individual cases. Disabling cookies may limit the functionality of our website. </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <SectionFeatures2 />
  <section class="section is-medium">
    <div class="container">
      <div class="columns">
        <div class="column is-offset-3 is-6">
          <div class="content is-medium">
            <p> By using our website you consent to the collection, processing and use of data as described below. Our website can be visited without registration. This data such as pages called or name of the retrieved file, date and time are stored on the server for statistical purposes, without this data are directly related to your person. Personal data, in particular name, address or e-mail address are collected as far as possible on a voluntary basis. Without your consent, the data will not be passed on to third parties. </p>
            <h2> Web &amp; Social Media </h2>
            <h3> Contacting Us </h3>
            <p> If you contact us by means of a form on the website or by e-mail, your data will be stored for a period of 12 months in order to process the request and in case of follow-up questions. We will not share this information without your consent. </p>
            <h3> Cookies </h3>
            <p> Our website uses so-called cookies. These are small text files that are stored on your device using the browser and do net present any harm. We use cookies to make our offer user-friendly. Some cookies remain stored on your device until you delete them. They allow us to recognize your browser on your next visit. If you object to this, you can set up your browser so that it informs you about the setting of cookies and you allow this only in individual cases. Disabling cookies may limit the functionality of our website. </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <SectionCenter />
</layout-default>
</template>

<script>
import SectionCenter from '@/components/SectionCenter.vue'
import SectionFeatures2 from '@/components/SectionFeatures2.vue'

import SectionGrid from '@/components/SectionGrid.vue'
import LayoutDefault from '@/layouts/LayoutDefault.vue'

export default {
  name: 'About',
  components: {
    SectionCenter,
    SectionFeatures2,
    SectionGrid,
    LayoutDefault
  }
}
</script>
