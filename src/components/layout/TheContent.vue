<template>
    <div class="m-content-container">
<div class="m-content">
    <Slide />
</div>
    </div>
</template>

<script>
import Slide from "../child/Slide.vue";
    export default {
        components:{
            Slide
        }
    }
</script>

<style lang="scss" scoped>
.m-content-container {
      background-color:#E5E5E5;
    // height: 100vh;
      display: flex;
    flex-direction: column;
    align-items: center;
.m-content {
  
}
}

</style>