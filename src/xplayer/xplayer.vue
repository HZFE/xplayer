<template>
 <div class="x-player">
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
  @import "//at.alicdn.com/t/font_224096_t3es4e3cae89f6r.css";
  .x-player {

  }
</style>
