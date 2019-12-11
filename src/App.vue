<template>
  <v-app>
    <v-content>
      <appToolbar/>
    </v-content>
  </v-app>
</template>

<script>
import appToolbar from './components/appToolbar';

export default {
  name: 'App',

  components: {
    appToolbar,
  },

  data: () => ({
    //
  }),
};
</script>
