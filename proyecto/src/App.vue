<template>
  <v-app>
    <HomeView></HomeView>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import HomeView from './views/HomeView.vue';

export default {
    name: "App",
    data: () => ({
    //
    }),
    components: { HomeView }
}
</script>
