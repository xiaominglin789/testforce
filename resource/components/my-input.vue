<template>
  <div class="app">
    <input type="text" v-model="city" placeholder="请输入商城ID" />
  </div>
</template>

<script>
export default {
  name:'mall2ncc',
  components: {},
  props: {},
  data () {
    return {
      city: ''
    }
  }
}
</script>

<style scoped>
</style>
