<template>
  <div class="app">
    <table>
      <tr>
        <td>序号</td>
        <td>名称</td>
        <td>代码</td>
      </tr>
      <td v-for="(item, index) in list" :key="item.id">
        <span>{{ index + 1}}</span>
        <span>{{ item.name }}</span>
        <span>{{ item.code }}</span>
      </td>
    </table>
  </div>
</template>

<script>
export default {
  name:'my-list',
  components: {},
  props: {
    sn: {
      type: String,
      default: ''
    }
  },
  data () {
    return {
      city: '',
      list: [
        { name: '北京市', code: '100100', id: 1 },
        { name: '上海市', code: '100600', id: 2 },
        { name: '天津市', code: '100800', id: 3 },
        { name: '重庆市', code: '100900' },
        { name: '广东省', code: '101000' },
        { name: '广西省', code: '101100' },
        { name: '山西省', code: '101200' }
      ]
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
