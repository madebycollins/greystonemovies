<template>
  <div>
    <!-- Navbar -->
    <Navbar />
    <!-- END Navbar -->

    <!-- Page Container -->
    <b-container class='page' fluid>
      <!-- Page content -->
      <nuxt />
      <!-- END content -->
    </b-container>
    <!-- END Page Container -->
  </div>
</template>

<script>
export default {
  name: 'default'
}
</script>

<style scoped>
.page {
  margin: 30px;
}
</style>
