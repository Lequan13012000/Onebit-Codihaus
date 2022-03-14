<template>
  <div>
    <TheHeader />
    <TheContent />
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from "../layout/TheHeader.vue";
import TheContent from "../layout/TheContent.vue";
import TheFooter from "../layout/TheFooter.vue";
export default {
  components: {
    TheHeader,
    TheContent,
    TheFooter,
  },
};
</script>

<style lang="scss" scoped>
</style>