<template>
  <div v-if="blok.headline" class="teaser" v-editable="blok">
    <h1>{{blok.headline}}</h1>
    <div>{{blok.content}}</div>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
