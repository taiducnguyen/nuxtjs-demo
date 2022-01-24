<template>
  <header class="header">
    <div class="mainNavigation">
      <div class="navigationLogo">
        <NuxtLink to="/about">
          <nuxt-img src="/images/electrolux_logo_sg.svg" alt="Elextrolux Logo" />
        </NuxtLink>
      </div>
      <div class="navigationMenu">
        <Link href="/">
          <a class="navigationItem">Products</a>
        </Link>
        <Link href="/">
          <a class="navigationItem">Support</a>
        </Link>
        <Link href="/">
          <a class="navigationItem">Promotion</a>
        </Link>
      </div>
    </div>
  </header>
</template>

<script lang="ts">
export default {
  name: 'HeaderComponent'
}
</script>
