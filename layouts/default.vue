<template>
  <div class="container mx-auto">
    <Header></Header>

    <nuxt />
  </div>
</template>

<script>
export default {
  mounted() {
    window.dataLayer = window.dataLayer || []
    function gtag() {
      window.dataLayer.push(arguments)
    }
    gtag('js', new Date())

    gtag('config', 'UA-203010067-1')
  },
}
</script>
