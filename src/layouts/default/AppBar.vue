<template>
  <v-app-bar :elevation="2">
    <v-app-bar-title>
      <router-link to="/" style="text-decoration: none; color: inherit;">
          <span class="title text-uppercase mx-4">Edward Burke</span>
      </router-link>
    </v-app-bar-title>
    <v-divider vertical></v-divider>
      <v-btn variant="text" class="mx-2">About</v-btn>
    <v-divider vertical></v-divider>
      <v-btn variant="text" class="mx-2">Projects</v-btn>
    <v-divider vertical></v-divider>
      <v-btn variant="text" class="mx-2">Other</v-btn>
    <v-divider vertical class="mr-2"></v-divider>
  </v-app-bar>
</template>

<script lang="ts" setup>
  //
</script>