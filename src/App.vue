<template>
  <div id="app">
    <Logo />
  </div>
</template>

<script>
import Logo from './components/Logo.vue'

export default {
  name: 'app',
  components: {
    Logo
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lora&display=swap');

:root {
  --green: hsl(155deg 16% 76%);
  --sand: hsl(59deg 6% 70%);
  --grey: hsl(59deg 1% 84%);
  }

body {
  background-color: var(--grey);
}
#app {
  font-family: 'Lora', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
