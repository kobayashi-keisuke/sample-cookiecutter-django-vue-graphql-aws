<template>
  <footer class="footer">
    <p>Version {{ version }}</p>
    <p>© 2020 test name</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      version: process.env.VUE_APP_VERSION
    }
  }
}
</script>

<style lang="scss" scoped>
.footer {
  padding-top: 3rem;
  padding-bottom: 3rem;
  text-align: center;
}
</style>
