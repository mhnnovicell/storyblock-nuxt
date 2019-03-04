<template>
  <div class="page" v-editable="blok">
    <component :key="blok._uid" v-for="blok in blok.body" :blok="blok" :is="blok.component"></component>
       <ul class="nav-links">
        <nuxt-link to="/ " tag="li" class="nav-link"><a>All Posts</a></nuxt-link>
        <nuxt-link to="/about" tag="li" class="nav-link"><a>About</a></nuxt-link>
      </ul>
  </div>
</template>

<script>
export default {
  props: ['blok']
}
</script>
