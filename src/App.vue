<template>
  <v-app>
    <v-main class="backgroundColor">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
.backgroundColor {
  background-color: white;
}
</style>