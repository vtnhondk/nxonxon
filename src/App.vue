<template>
  <div id="app">
    <ComingSoon author="Nhơn Võ" year="2018"/>
  </div>
</template>

<script>
import ComingSoon from "./components/ComingSoon.vue";

export default {
  name: "app",
  components: {
    ComingSoon
  }
};
</script>

<style src="./styles/app.css"/>
