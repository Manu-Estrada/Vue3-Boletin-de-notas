<script setup>

const props = defineProps({
  title:{
    type: String,
    required: true,
  }
});
</script>
<template>
  <header class="header">
    <h1>{{props.title}}</h1>
  </header>
</template>
<style lang="scss" scoped>

header{
  display: flex;
  align-items: center;
  justify-content: center;
  color: cadetblue;
  
}
</style>
