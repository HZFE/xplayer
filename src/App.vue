<template>
  <div id="app">
    <div class="player">
      <xplayer
        :src="options.src">
      </xplayer>
    </div>
  </div>
</template>

<script>
import xplayer from './xplayer'
export default {
  name: 'app',
  data () {
    return {
      options: {
        src: 'http://ofyaji162.bkt.clouddn.com/%E6%88%91%E5%AE%B3%E6%80%95.mp4'
      }
    }
  },
  components: {
    xplayer
  }
}
</script>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }

  .player {
    display: flex;
    justify-content: center;
    max-width: 100%;
  }
</style>
