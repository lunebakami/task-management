<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Button/>
    <TaskList/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TaskList from './components/TaskList.vue'
import Button from './components/Button'

export default {
  name: 'App',
  components: {
    TaskList,
    Button
  }
}
</script>

<style>
html {
  background-color: #2c3e50;
  display:flex;
  justify-content: center;
  font-family: 'Roboto', sans-serif;
  font-weight: bold;
}

#app {
  display: grid;
  width: 300px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 5%;
}
</style>
