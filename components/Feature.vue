<template>
  <div v-if="blok.name" v-editable="blok" class="column feature">
    {{blok.name}}
    <component :key="blok._uid" v-for="blok in blok.columns" :blok="blok" :is="blok.component"></component>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
