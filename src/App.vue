<template>
  <div id="app">
    <NavMenu />
    <Header />
    <Hero />
    <About />
    <Roadmap />
    <Team />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import NavMenu from './components/NavMenu.vue'
import About from './components/About.vue'
import Roadmap from './components/Roadmap.vue'
import Team from './components/Team.vue'

export default {
  name: 'App',
  components: { Header, Hero, NavMenu, About, Roadmap, Team },
}
</script>

<style lang="scss">
* {
  margin:0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  height:1500px;
}

body {
  font-family: 'Open Sans', sans-serif;
  background-image: url("./assets/space-background.png");
  background-size: cover;
}

</style>
