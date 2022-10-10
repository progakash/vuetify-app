<template>
  <v-app class="grey lighten-4">
    <NavbarApp />
    <v-content class="mx-4 mb-4">
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import NavbarApp from './components/NavbarApp'
export default {
  name: 'App',
  components: { NavbarApp },
  data: () => ({
    //
  }),
}
</script>
