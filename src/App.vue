<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center"></div>
    </v-app-bar>

    <v-content>
      <DesktopList />
    </v-content>
  </v-app>
</template>

<script>
import DesktopList from './components/DesktopList'

export default {
  name: 'App',

  components: {
    DesktopList
  }
}
</script>
