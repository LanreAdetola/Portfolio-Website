<template>
  <div id="app">
    <MainCard/>
    <ProjectsCard/>
  </div>
</template>

<script>
import MainCard from './components/MainCard.vue';
import ProjectsCard from './components/ProjectsCard.vue';

export default {
  name: 'App',
  components: {
    MainCard,
    ProjectsCard
  }
}
</script>

<style>
body{
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #d6edff ;
}
</style>
