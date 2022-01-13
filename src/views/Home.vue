<template>
  <div class="allPage">
    <Marquees></Marquees>
    <div class="row g-0">
      <div class="col-sm-8">
        <Video></Video>
      </div>
      <div class="col-sm-4">
        <Image></Image>
        <TimeTable></TimeTable>
      </div>
    </div>
  </div>
</template>

<script>
import Marquees from '@/components/Marquees.vue'
import Video from '@/components/Video.vue'
import Image from '@/components/Image.vue'
import TimeTable from '@/components/Timetable.vue'
export default {
  components: {
    Marquees,
    Video,
    Image,
    TimeTable
  }
}
</script>

<style lang="scss" scoped>
</style>
