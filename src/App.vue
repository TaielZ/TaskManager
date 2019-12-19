<template>
  <div id="app">
    <TaskContainer title="Deadly"/>
        <TaskContainer title="Otro Deadly"/>
    <Deadly />
  </div>
</template>

<script>

import TaskContainer from './components/TaskContainer'
import Deadly from './components/Deadly'

export default {
  name: 'app',
  components: {
    TaskContainer ,
    Deadly ,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
