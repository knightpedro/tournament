<template>
  <v-app>
    <NavBar></NavBar>
    <v-main>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import NavBar from './shared/NavBar.vue';

export default Vue.extend({
  name: 'App',
  components: { NavBar }
});
</script>
