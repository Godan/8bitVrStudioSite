<template>
  <div class="container">
    <div>
      <h1 class="title">
        8bitVR<br>
        Studio
      </h1>
      <h2 class="subtitle">
        Retro game studio & Streamers Production
      </h2>
      <div class="navibar">
        <navibar />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Navibar from '~/components/Navibar.vue'

export default Vue.extend({
  components: {
    Navibar
  },
  layout: 'top'

})
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: black;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #EEEEEE;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 22px;
  color: #aaaaaa;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.navibar {
  padding-top: 55px;
}
</style>
