<template>
  <v-footer color="indigo" padless>
    <v-col class="text-center white--text" cols="12">
      {{ new Date().getFullYear() }} —
      <strong
        ><a target="_blank" href="https://github.com/Fedekiller"
          >Federico Leguizamon
        </a>
        (Front-End TP Final)</strong
      >
    </v-col>
  </v-footer>
</template>
<script>
export default {};
</script>

<style>
a {
  color: #34d1bf !important;
  text-decoration: none;
}
</style>
