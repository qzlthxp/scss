<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <div class="content">
    <h1>hi</h1>
    <p>paragraph</p>
    <article>
      <a href="">
        baidu
        <img src="" alt="123" />
      </a>
    </article>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
@import '../src/styles/1';
@import '../src/styles/5';
#app {
  font-family: $plain-font;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: $app;
  color: $highlight-color;
  margin-top: 60px;
  @include rounded-corners;
  background-color: darkblue;
}
</style>
