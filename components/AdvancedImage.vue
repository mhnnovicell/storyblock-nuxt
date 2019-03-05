<template>
  <div class="image" v-editable="blok">
    <img v-bind:src="blok.img.image" v-bind:alt="blok.img.alt_tag">
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>

<style>
.image img {
  width: 10vw;
  height: 10vh;
}
</style>
