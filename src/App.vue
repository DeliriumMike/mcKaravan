<template>
  <v-app>
    <AppHeader></AppHeader>
    <AppNavBar></AppNavBar>
  </v-app>
</template>

<script>
  import AppHeader from '@/components/AppHeader.vue'
  import AppNavBar from '@/components/AppNavBar.vue'

  export default {
    name: 'App',

    components: {
      AppHeader,
      AppNavBar,
    },

    data: () => ({
      //
    }),
  };
</script>