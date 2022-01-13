<template>
<div class="marquee">
  <ul class="marquee-container list-unstyled mb-0">
    <li>
      <h5 class="mb-0 mt-2 px-5">
        <i class="fas fa-bullhorn"></i>
      </h5>
      <span class="mb-0">跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈文字跑馬燈</span>
    </li>
  </ul>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.marquee{
  overflow:hidden;
  background-color: #000;
  height: 20vh;
  display: flex;
  align-items: center;
}
.marquee-container li {
  display: flex;
  white-space: nowrap;
}
.marquee-container li h5, span{
  color: #97DFFF;
  font-size: 48px;
  font-weight: 700;
  font-family: Roboto;
}
</style>
