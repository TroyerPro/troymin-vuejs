<template>
  <div class="container" id="app">
    <div class="row">
      <div class="col-12">
        <img src="./assets/logo.png">
        <router-view/>
      </div>
      <div class="col-6">
        <button class="btn btn-primary">Test</button>
      </div>
      <div class="col-6">
        TEST
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'App'
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
<style lang="scss">
@import './styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>
