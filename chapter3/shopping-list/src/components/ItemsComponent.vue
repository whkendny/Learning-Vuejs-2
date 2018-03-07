<!--渲染并操作列表 -->
<template>
  <div>
    <item-component v-for="item in items" :item="item"></item-component>
  </div>
</template>

<script>
  import ItemComponent from './ItemComponent'

  export default {
    components: {
      ItemComponent
    },
    props: ['items']
  }
</script>

<style scoped>
</style>
