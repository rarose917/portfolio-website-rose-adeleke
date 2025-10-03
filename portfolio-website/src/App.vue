
<template>
  <div id="app">

    <div class=" container">
      <div class="row text-black bg-opacity-75 ">
        <div class="col">
          <h1 style="font-size: 15px; font-family: 'Poppins', sans-serif; text-decoration-line: underline;">{{ title }}
          </h1>

        </div>
      </div>
      <NavDsgn />
      <HomePG />
    </div>
  </div>
</template>

<script>
import HomePG from './components/HomePG.vue'
import NavDsgn from './components/NavDsgn.vue'

export default {
  name: "App",
  components: {
    NavDsgn,
    HomePG,
  },
  data() {
    return {
      title: "Rose A."
    }
  }
}
</script>

<style>
#app {
  min-height: 100vh;
  background: url('@/assets/layered-waves-haikei.svg') no-repeat center center;
  background-size: cover;
}


body {
  font-family: 'Roboto', sans-serif;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  height: 100%;
  margin: 0;
}
</style>
