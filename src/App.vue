<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
window.addEventListener('orientationchange',setRem);
window.addEventListener('resize',setRem);
setRem();
function setRem() {
  var html = document.querySelector('html');
  var width = html.getBoundingClientRect().width;
  html.style.fontSize = width/16+"px"
}
export default {
  name: 'App'
}
</script>

<style scoped lang="scss">

</style>
