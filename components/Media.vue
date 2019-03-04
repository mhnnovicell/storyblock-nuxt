<template>
  <div class="image" v-editable="blok">
<img v-bind:src="blok.image" alt="blok.name" />
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>

<style>
.image img{
  width: 60vw;
  height: 50vh;
}
</style>
