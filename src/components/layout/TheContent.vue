<template>
    <div class="m-content-container">
<div class="m-content">
    <Slide />
    <TopList />
    <OnGoing />
    <!-- <div class="m-content-bottom"> -->
  <Trending />
    <!-- </div> -->
  
</div>
    </div>
</template>

<script>
import Slide from "../child/Slide.vue";
import TopList from "../child/TopList.vue";
import OnGoing from "../child/OnGoing.vue";
import Trending from "../child/Trending.vue";
    export default {
        components:{
            Slide,
            TopList,
            OnGoing,
            Trending
        }
    }
</script>

<style lang="scss" scoped>
.m-content-container {
      background-color:#f4f5f6;
    // height: 100vh;
      display: flex;
    flex-direction: column;
    align-items: center;
.m-content {
  .m-content-bottom{
      background-color: #fff;
  }
}
}

</style>