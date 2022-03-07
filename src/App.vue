<template>
  <div id="app">
    <MyHeader :links="links" ></MyHeader>
    <MyMain></MyMain>
    <MyFooter :products="products"></MyFooter>
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  data() {
        return {
            links: [
              {
                text: 'Home',
              },
              {
                text: 'Service',
              },
              {
                text: 'About',
              },
              {
                text: 'Videos',
              },
              {
                text: 'Blog',
              },
              {
                text: 'Store',
              },
            ],
            products: [
              {
                shop:'>The best protein shake',
              },
              {
                shop:'>Ultimate cardio workout',
              },
              {
                shop:'>New juice available',
              },
              {
                shop:'>Tips to find training partners',
              },
              {
                shop:'>20 best healthy recipes',
              },
            ],
          }
    },
  components: {
    MyHeader,
    MyMain,
    MyFooter,

  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&family=Short+Stack&display=swap');
html {
  font-family: 'Roboto', sans-serif;
}

</style>

