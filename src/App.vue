<template>
  <v-app class="bg-grey-lighten-3">
    <Header />

    <v-main>
      <router-view/>
    </v-main>

  </v-app>
</template>

<script>
import Header from './components/HeaderComponent.vue';
export default {
  name: 'App',
  components: {
    Header,
  },
  data: () => ({
    //
  }),
}
</script>
