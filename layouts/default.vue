<template>
  <div>
    <HeaderComponent />
    <nuxt />
    <FooterComponent />
  </div>
</template>

<script lang="ts">
import HeaderComponent from '../components/header.vue'
import FooterComponent from '../components/footer.vue'

export default {
  name: 'LayoutDefault',
  components: {
    HeaderComponent,
    FooterComponent
  }
}
</script>
