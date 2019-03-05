<template>
  <div class="grid" v-editable="blok">
    <div v-if="blok.bootstrap" v-bind:class="blok.bootstrap.small">
      <component :key="blok._uid" v-for="blok in blok.columns" :blok="blok" :is="blok.component"></component>
    </div>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
