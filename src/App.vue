<template>
  <div id="app">
    <GithubCorner url="https://github.com/Roeefl/vue-github-corners" flipOnHover>
    </GithubCorner>
  </div>
</template>

<script>
  import GithubCorner from './GithubCorner'

  export default {
    name: 'app',
    components: {
      GithubCorner
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
