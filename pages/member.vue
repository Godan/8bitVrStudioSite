<template>
  <div class="container">
    <div class="max-row">
      <h1 class="title">
        Member
      </h1>
      <div class="profile">
        <h2 class="profile">
          夢オチ
        </h2>
        <h3 class="profile">
          yumeochi
        </h3>
        <img src="../static/5t67v-7i_400x400.jpg" class="br-max user-icon profile">
        <div>
          <p class="center-text">
            準備中
          </p>
          <div class="center-text profile-icons">
            <a href="https://twitter.com/yumeoti_Mk2"><font-awesome-icon class="twitter" :icon="['fab', 'twitter']" /></a>
            <!-- <a href="https://twitter.com/yumeoti_Mk2"><font-awesome-icon class="youtube" :icon="['fab', 'youtube']" /></a> -->
          </div>
        </div>
      </div>
      <div class="profile">
        <h2 class="profile">
          ゴダン
        </h2>
        <h3 class="profile">
          Godan
        </h3>
        <img src="../static/VoGlIWlc.jpg" class="br-max user-icon profile">
        <div>
          <p class="center-text">
            ネットの海をさまよっている。<br>
            好きな音楽は根暗な曲。<br>
            心も根暗。
          </p>
        </div>
        <div class="center-text profile-icons">
          <a href="https://twitter.com/godan09"><font-awesome-icon class="twitter" :icon="['fab', 'twitter']" /></a>
          <!-- <a href="https://twitter.com/yumeoti_Mk2"><font-awesome-icon class="youtube" :icon="['fab', 'youtube']" /></a> -->
        </div>
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
div.profile{
  padding-left: 0;
  padding-bottom: 120px;
  text-align: center;
}
h2.profile{
  width: 100%;
  font-weight: 300;
  font-size: 22px;
  vertical-align: middle;
  text-align: center;
}
h3.profile{
  width: 100%;
  font-weight: 300;
  font-size: 22px;
  vertical-align: middle;
  padding-bottom: 30px;
  text-align: center;
}

img.profile{
  vertical-align: middle;
  text-align: center;
}

.profile-icons{
  padding-top: 30px;

}

.yumeochi-backcolor{
  background-color: brown;
}

.navibar {
  padding-top: 55px;
}

.user-icon{
  width: 200px;
  height: 200px;
  }
</style>
