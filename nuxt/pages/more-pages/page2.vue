<template>
  <div v-title data-title="Page2">
    <div @click="handleRouterPush">this is page2</div>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {

    }
  },
  methods:{
    handleRouterPush(){
      this.$router.push({ path: '/' })
    }
  }
})
</script>

<style lang="less" scoped>

</style>
