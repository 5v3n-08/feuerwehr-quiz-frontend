<template>
  <div class="flex justify-center align-items-center">
    <div class="bg-image h-screen w-screen" />
    <v-card class="">
      <h1>Anmeldung</h1>
    </v-card>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  layout: 'blank',
})
</script>

<style>
.bg-image {
  position: fixed;
  background-image: url('~/assets/images/auth_background.jpg');
  background-size: cover;
}
</style>
