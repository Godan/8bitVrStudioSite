<template>
  <div class="container">
    <div>
      <h1 class="title">
        About
      </h1>
      <h2 class="subtitle">
        8bit<レトロ>をVR<現代>に
      </h2>
      <p>TOOD: ここにいい感じの画像</p>
      <div>
        <p>
          色々あって作った仲間内のサークル<br>
          一人がボドゲを作り。一人は動画撮ったりなんやかんやしたり。一人は配信をしたり。<br>
          地球に未開拓地はすでに無く。宇宙を開拓するには早すぎる時代。 <br>
          僕たちはこのVRの世界に新しい開拓地を創ろう。
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
  display: flex;
  /* justify-content: center; */
  /* align-items: center; */
  /* text-align: center; */
  background-color: white;
  margin-top: 50px;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #000;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 22px;
  color: #888;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.navibar {
  padding-top: 55px;
}
</style>
