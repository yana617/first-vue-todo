<template>
  <div id="app" class="container">
    <img class="logo" alt="Vue logo" src="./assets/logo.png">
    <h6 class="app-title">It is the my first Vue App that I have done. I liked it :)</h6>
    <todo-list></todo-list>
  </div>
</template>

<script>
import TodoList from './components/TodoList';

export default {
  name: 'app',
  components: {
    TodoList,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
  font-size: 22px;
}
* {
  box-sizing: border-box;
}
.container {
  max-width: 600px;
  margin: 0 auto;
}
.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
.app-title {
  text-align: center;
  font-size: 20px;
}
</style>
