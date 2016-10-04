<template>
  <div id="app">
    <header-nav></header-nav>
    <sidebar></sidebar>
  </div>
</template>

<script>
import Header from './components/Header';
import Sidebar from './components/Sidebar';

export default {
  components: {
    Header,
    Sidebar,
  },
};
</script>

<style lang="postcss">
html {
  height: 100%;
  font-size: 16px;
  line-height: 1.5;
}

body {
  height: 100%;
}

#app {
  height: 100%;
  color: #2c3e50;
  background-color: #FAFAFA;
  font-family: 'Open Sans','Helvetica Neue', Helvetica, 'Arial', '游ゴシック', YuGothic, 'ヒラギノ角ゴ ProN W3', 'Hiragino Kaku Gothic ProN', 'メイリオ', Meiryo, sans-serif;
}
</style>
