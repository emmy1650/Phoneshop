<template>
 <div>
  <HeaderComponent></HeaderComponent>
</div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue"

export default {
  name: 'App',
  components:{
    HeaderComponent
  }

}
</script>

<style>
*{
  padding:0;
  margin: 0;
  box-sizing: border-box;
  
}
</style>
