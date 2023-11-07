<template>
  <div class="app">
    主页模块
  </div>
</template>

<script>
export default {
  name:'mall2ncc',
  components: {},
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
        mallContactPhone: '',

      }
    }
  }
}

<style scoped>
.app {}
</style>
