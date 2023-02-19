<template>
  <v-app-bar :elevation="2">
    <v-app-bar-title>
      <router-link to="/" style="text-decoration: none; color: inherit;">
          <span class="title text-uppercase mx-4">Edward Burke</span>
      </router-link>
    </v-app-bar-title>
      <v-divider vertical></v-divider>
      <div class="wip-wrapper">
        <v-btn variant="text" class="wip-wrapper" disabled>About</v-btn>
        <div variant="text" class="wip-text">WIP</div>
      </div>
      <v-divider vertical></v-divider>
      <div class="wip-wrapper">
        <v-btn variant="text" class="mx-2" disabled>Projects</v-btn>
        <div variant="text" class="wip-text">WIP</div>
      </div>
      <v-divider vertical></v-divider>
      <div class="wip-wrapper">
        <v-btn variant="text" class="mx-2" disabled>Other</v-btn>
        <div variant="text" class="wip-text">WIP</div>
      </div>
      <v-divider vertical class="mr-2"></v-divider>
  </v-app-bar>
</template>

<style>
  .wip-wrapper {
    position: relative;
  }
  .wip-text {
    position: absolute;
    padding-top: 25px;
    color: red;
    position: absolute;
    top: 0%;
    left: 35%;
  }
</style>

<script lang="ts" setup>
  //
</script>