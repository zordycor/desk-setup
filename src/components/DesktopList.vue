<template>
  <v-container>
    <v-row class="text-center">
      <Desktop />
    </v-row>
  </v-container>
</template>

<script>
import Desktop from './Desktop'
export default {
  name: 'DesktopList',

  components: {
    Desktop
  }
}
</script>
