<template>
  <div class="teaser" v-editable="blok">
    <h1>{{blok.headline}}</h1>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
