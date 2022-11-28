<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MyComponent msg="This is my component!"/>
    <MySecondComponent msg="This is my second component!"/>
    <MyThirdComponent msg="This is my third component!" />
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue'
import MySecondComponent from './components/MySecondComponent.vue';
import MyThirdComponent from './components/MyThirdComponent.vue'
export default {
  name: 'App',
  components: {
    MyComponent,
    MySecondComponent,
    MyThirdComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
