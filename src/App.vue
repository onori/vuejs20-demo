<template>
  <div id="app">
    <hello></hello>
    <sidebar></sidebar>
</template>

<script>
import Hello from './components/Hello';
import Sidebar from './components/Sidebar';

export default {
  components: {
    Hello,
    Sidebar,
  },
};
</script>

<style>
html {
  height: 100%;
}

body {
  height: 100%;
}

#app {
  color: #2c3e50;
  font-family: 'Open Sans','Helvetica Neue', Helvetica, 'Arial', '游ゴシック', YuGothic, 'ヒラギノ角ゴ ProN W3', 'Hiragino Kaku Gothic ProN', 'メイリオ', Meiryo, sans-serif !default;
}
</style>
