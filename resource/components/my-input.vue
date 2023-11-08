<template>
  <div class="app">
    <input type="text" v-model="city" placeholder="请输入商城ID" @change="handleChangeEvent" />
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
  },
  methods: {
    handleChangeEvent () {
      console.log('输入了: ', this.city)
    }
  }
}
</script>

<style scoped>
</style>
