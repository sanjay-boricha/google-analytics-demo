<template>
  <div>analytics</div>
</template>

<script>
export default {
  mounted() {
    window.dataLayer = window.dataLayer || []
    function gtag() {
      window.dataLayer.push(arguments)
    }
    gtag('js', new Date())

    gtag('config', 'G-MQC76ZCCT2')
  },
}
</script>
