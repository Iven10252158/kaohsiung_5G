<template>
    <div class="video mb-0">
        <div class="mb-0">
            <YoutubeVue3 videoid="2mCSYvcfhtc"
            style='width:100% ;height:80vh'
            ref="youtube"
            :autoplay="autoplay"
            @played="onPlayed"
            @ended="onEnded"/>
        </div>
    </div>
</template>

<script>
import { YoutubeVue3 } from 'youtube-vue3'

export default {
  components: {
    YoutubeVue3
  }
}
</script>
