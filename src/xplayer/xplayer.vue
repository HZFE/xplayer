<template>
 <div class="xplayer">
   <xvideo
     :src="src"
   ></xvideo>
 </div>
</template>

<script>
import xvideo from './xvideo'
export default {
  data: function () {
    return {
    }
  },
  props: {
    src: {
      type: String,
      require: true
    }
  },
  components: {
    xvideo
  }
}
</script>

<style lang="scss" scoped>
  .xplayer {
    
  }
</style>
