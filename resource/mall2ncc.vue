<template>
  <div class="app">
    主页模块
    <myList />
  </div>
</template>

<script>
import myList from './components/my-list'

export default {
  name:'mall2ncc',
  components: {
    myList
  },
  props: {},
  data () {
    return {
      formInline: {
        mallId: '',
        nccId: '',
        mallName: '',
        nccName: '',
        mallAddress: '',
        nccAddress: '',
        mallPhone: '',
        nccPhone: '',
        mallContact: '',
        nccContact: '',
        mallContactPhone: ''
      }
    }
  }
}
</script>

<style scoped>
.app {}
</style>
