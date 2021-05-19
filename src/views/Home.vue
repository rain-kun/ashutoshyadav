<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header />
    <SideBar/>
    <Content/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import SideBar from '@/components/SideBar.vue'
import Content from '@/components/Content.vue'

export default {
  name: 'Home',
  components: {
    Header,
    SideBar,
    Content,
  }
}
</script>

<style>
html, body {
  background-color: #0e546a;
}
</style>