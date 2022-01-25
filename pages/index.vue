<template>
  <main>
    <h1 class="title">
      Measure page quality
    </h1>

    <p class="description">
      Test your pages in a lab environment powered by PageSpeed Insights. Then get tips and recommendations to improve your user experience. For field performance, see the
      <a target="_blank" href="https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect">PageSpeed Insights</a> tool.
    </p>

    <nuxt-img src="/testing.jpg" alt="Elextrolux Logo" width="400" height="400" />
  </main>
</template>

<script lang="ts">
export default {
  name: 'PageIndex'
}
</script>

<style scoped>
.container {
  min-height: 100vh;
  padding: 0 0.5rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

main {
  padding: 5rem 0;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.title {
  margin: 0;
  line-height: 1.15;
  font-size: 4rem;
}

.title,
.description {
  text-align: center;
}

.description {
  line-height: 1.5;
  font-size: 1.5rem;
}
</style>
<style>
html,
body {
  padding: 0;
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid Sans, Helvetica Neue, sans-serif;
}

* {
  box-sizing: border-box;
}
</style>
