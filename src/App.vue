<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-tabs 
        grow
      >
        <v-tab>
          Foo
        </v-tab>
        <v-tab>
          Bar
        </v-tab>
        <v-tab>
          FooBar
        </v-tab>
      </v-tabs>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
