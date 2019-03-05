<template>
  <div class="form" v-editable="blok">{{blok.field}}</div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
