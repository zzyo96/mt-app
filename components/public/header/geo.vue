<template>
  <div class="m-geo">
    <i class="el-icon-location"/>北京市
    <nuxt-link
      class="changeCity"
      to="/changeCity">
      切换城市
    </nuxt-link>
    [香河 廊坊 天津]
  </div>
</template>

<script>
    export default {
        name: "geo.vue"
    }
</script>

<style scoped>

</style>
