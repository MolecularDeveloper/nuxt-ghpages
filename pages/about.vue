<template>
  <section class="container">
    <div>
      <h1 class="hero">
        About Page
      </h1>
      <h2 class="subtitle">
        Nuxt Project - Implementation
      </h2>
      <div class="columns">
        
        <div class="column">
          <div class="box">
            <button class="button is-primary">Allavino</button>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <nuxt-link to="/">
            <button class="button is-info">index</button>
          </nuxt-link>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <nuxt-link to="/home">
            <button class="button is-success">Home</button>
          </nuxt-link>
          </div>
        </div>
      
      </div>
    </div>
  </section>
</template>

<script>
</script>

<style lang="scss">


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
