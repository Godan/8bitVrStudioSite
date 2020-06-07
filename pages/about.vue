<template>
  <div class="container">
    <div class="max-row">
      <h1 class="title">
        About
      </h1>
      <h2 class="subtitle">
        8bit<レトロ>をVR<現代>に
      </h2>
      <p>TOOD: ここにいい感じの画像</p>
      <div class="center-text">
        <p class="center-text">
          色々あって作った仲間内のサークル<br>
          一人がボドゲを作り。一人は動画撮ったりなんやかんやしたり。一人は配信をしたり。<br>
          地球に未開拓地はすでに無く。宇宙を開拓するには早すぎる時代。 <br>
          僕たちは、この「VR」の世界に新しい開拓地を創ろう。
        </p>
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
  }
})
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  min-width: 100vh;
  display: flex;
  /* justify-content: center; */
  /* align-items: center; */
  /* text-align: center; */
  background-color: white;
  margin-top: 50px;
}

.navibar {
  padding-top: 55px;
}

</style>
