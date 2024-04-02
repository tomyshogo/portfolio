<template>
  <div id="app">
    <Header/>
    <Top/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Top from './components/Top.vue';
export default {
  name: 'App',
  components: {
    Header,
    Top,
    Footer
  }
}
</script>

<style>
  /*-- ↓最初に読み込みたいリセットCSSを先に読み込みます */
@import 'https://unpkg.com/ress@4.0.0/dist/ress.min.css';
@import './CSS/style.css'; /* CSS内でのインポート */
</style>