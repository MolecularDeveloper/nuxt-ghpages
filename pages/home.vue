<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        MolecularDeveloper
      </h1>
      <h2 class="subtitle">
        <a href="mailto:moleculardeveloper@gmail.com">MolecularDeveloper@gmail.com</a>
      </h2>
      <div class="columns">
        <div class="column"><nuxt-link to="/about"><button class="button isprimary">About</button></nuxt-link></div>
        <div class="column"><nuxt-link to="/home"><button class="button isprimary">Home</button></nuxt-link></div>
        <div class="column"><nuxt-link to="/"><button class="button isprimary">Index</button></nuxt-link></div>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
export default {
  components: {
    AppLogo
  }
}
</script>

<style lang="scss">
@import 'node_modules/bulma/bulma.sass';

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 50px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.subtitle a {
  color: darkgrey;
}

.links {
  padding-top: 15px;
}
</style>
