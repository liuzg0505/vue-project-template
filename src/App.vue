<template>
  <div>
      Hello Vue
      <hr>
      {{name}}

      <router-view></router-view>
  </div>
</template>



<script>
export default {
  data(){
      return {
          name: "张三"
      }
  }
}
</script>

<style>

</style>

