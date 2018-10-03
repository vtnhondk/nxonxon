<template>
  <div id="app">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">
    <ComingSoon author="Nhơn Võ" year="2018"/>
  </div>
</template>

<script>
import ComingSoon from './components/views/ComingSoon.vue';

export default {
  name: "app",
  components: {
    ComingSoon
  }
};
</script>

<style>
#app {
  height: 100%;
}

body {
  font-family: "Raleway", Helvetica, Arial MS, sans-serif;
  color: #ffffff;
  font-weight: 200;
  font-size: 12px;
  background-color: black;
  scroll-behavior: auto;
}

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
}
</style>
