<template>
  <div>
    <simple-map></simple-map>
  </div>
</template>

<script>

import simpleMap from './components/SimpleMap'

export default {
  components: {
    'simple-map': simpleMap
  }
}
</script>

<style>
  @import "../node_modules/leaflet/dist/leaflet.css";

</style>
