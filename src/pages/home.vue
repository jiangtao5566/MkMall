<template>
  <div>
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import NavFooter from '../components/NavFooter.vue'
import NavHeader from '../components/NavHeader.vue'
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'home',
  components: { 
    NavFooter,
    NavHeader
  }
  
}
</script>
