<template>
<div>
  <TheHeader />
  <TheContent />
</div>

</template>

<script>
import TheHeader from "../layout/TheHeader.vue";
import TheContent from "../layout/TheContent.vue";
export default {
  components: {
    TheHeader,
    TheContent
  },
};
</script>

<style lang="scss" scoped>
</style>