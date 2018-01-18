<template>
 <div class="xvideo">
   <video
     :poster="poster"
     webkit-playsinline=""
     playsinline=""
     crossorigin="anonymous"
     preload="preload"
     :src="src">
   </video>
 </div>
</template>

<script>
export default {
  data: function () {
    return {
    }
  },
  props: {
    src: {
      type: String,
      require: true
    },
    poster: {
      type: String,
    },
    preload: {
      type: String,
      default: 'none'
    }
  },
}
</script>

<style lang="scss" scoped>
 .xvideo {
   video {
     max-width: 100%;
   }
 }
</style>
