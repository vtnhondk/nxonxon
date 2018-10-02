<template>
  <div class="header">
    <h1>{{ author }} - {{ year }}</h1>
  </div>
</template>

<script>
export default {
  name: "ComingSoon",
  props: {
    author: String,
    year: String
  }
};
</script>

<style>
.header {
  margin: 0;
  padding: 15px;
}

h1 {
  font-size: 1em;
}
</style>
