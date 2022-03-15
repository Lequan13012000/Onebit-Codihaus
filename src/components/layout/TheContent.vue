<template>
  <div class="m-content-wrapper">

    <div class="m-content-top">
      <div class="m-content">
        <Slide />
        <TopList />
        <OnGoing />
        <Trending />
      </div>
    </div>
    <div class="m-content-bottom">
      <Recent />
    </div>
    <div class="m-content-top">
      <div class="m-content">
        <OneBit />
      </div>
    </div>
  </div>
</template>

<script>
import Slide from "../child/Slide.vue";
import TopList from "../child/TopList.vue";
import OnGoing from "../child/OnGoing.vue";
import Trending from "../child/Trending.vue";
import Recent from "../child/Recent.vue";
import OneBit from "../child/OneBit.vue";
export default {
  components: {
    Slide,
    TopList,
    OnGoing,
    Trending,
    Recent,
    OneBit,
  },
};
</script>

<style lang="scss" scoped>

.m-content-top {
  background-color: #f4f5f6;
  // height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  .m-content {
    margin-bottom: 59px;
    .m-content-bottom {
      background-color: #fff;
    }
  }
}
</style>