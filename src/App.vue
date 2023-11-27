<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <HeaderComp/>
  <HeaderBannerComp/>
  <BlogDetailsPage/>
  <FooterComp/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue' 
import BlogDetailsPage from './components/BlogDetailsPage.vue'
import HeaderComp from './components/HeaderComp.vue'
import HeaderBannerComp from './components/HeaderBannerComp.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    BlogDetailsPage,
    HeaderComp,
    HeaderBannerComp,
    FooterComp,
    

    // HelloWorld
  }
}
</script>

<style lang="scss">
* {
   margin: 0;
   padding: 0;
}
.center {
   padding-left: calc(50% - 1240px / 2);
   padding-right: calc(50% - 1240px / 2);
}
a {
   text-decoration: none;
}
</style>
