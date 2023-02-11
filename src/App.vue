<template>
  <div >
 
    <Navtion/>
    <Search/>
    <foot/>
  </div>

</template>

<script>
// import HelloWorld from './components/HelloWorld'
import Navtion  from './components/Nav.vue'
import Search  from './components/search.vue'
import foot  from './components/foot.vue'

export default {
  name: 'App',
  components: {
    Navtion,Search,foot
  }
}
</script>

<style>

</style>
