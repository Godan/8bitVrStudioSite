<template>
  <div>
    <nav>
      <div class="nav-wrapper">
        <a href="#" class="brand-logo">8Bit VR Studio.</a>
        <space>
          <div id="nav-mobile" class="right">
            <navibar />
          </div>
        </space>
      </div>
    </nav>
    <nuxt />
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

<style lang="scss" scoped>

@import  '~/assets/style/app.scss';

</style>
