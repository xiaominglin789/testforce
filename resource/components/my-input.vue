<template>
  <div class="app">
    <input type="text" v-model="city" placeholder="xxxxxxxxxx请输入商城IDxxxxxxxxxxxx"  @change="handleChange" />
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
    handleChange () {
      console.log('输入了: ', this.city)
    }
  }
}
</script>

<style scoped>
</style>
