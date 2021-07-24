<template>
  <div>
    <section class="container">
      <div>
        <Tutorial />
        <h1 class="title">
          nuxt-fundamentals
        </h1>
        <h2 class="subtitle">
          My gnarly Nuxt.js project
        </h2>
        <div class="links">
          <a href="https://nuxtjs.org/" target="_blank" class="button--green"
            >Documentation</a
          >
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            class="button--grey"
            >GitHub</a
          >
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Tutorial from "@/components/Tutorial.vue";
export default {
  components: {
    Tutorial
  }
};
</script>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 5px;
  word-spacing: 0px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 0px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
