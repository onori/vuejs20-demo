<template>
  <div id="app">
    <nav></nav>
    <sidebar></sidebar>
    <contents></contents>
    <footer-content></footer-content>
  </div>
</template>

<script>
import Header from './components/Header';
import Sidebar from './components/Sidebar';
import Contents from './components/Contents';
import Footer from './components/Footer';

export default {
  components: {
    Header,
    Sidebar,
    Footer,
  },
};
</script>

<style lang="postcss">
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
img {
  width: 100%;
}

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
  font-family: '游ゴシック', YuGothic, 'ヒラギノ角ゴ ProN W3', 'Hiragino Kaku Gothic ProN', 'メイリオ', Meiryo, sans-serif;
}

.container {
  width: 960px;
}

</style>
