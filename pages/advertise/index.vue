<template>
  <h1 class="red">
    Hello {{ name }}!
  </h1>
</template>

<script>
export default {
  name: 'AdvertiseManage',
  data () {
    return {
      name: 'hey'
    }
  }
}
</script>

<style>
  .red {
    color: red;
  }
</style>
