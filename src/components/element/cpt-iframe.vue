<template>
  <iframe loading="lazy" width="100%" height="100%" :src="option.attribute.url"></iframe>
</template>

<script>
export default {
  name: "cpt-iframe",
  title: 'iframe',
  icon: 'el-icon-s-promotion',
  group:'basic',
  props: {
    option: Object
  },
}
</script>

<style scoped>

</style>
