<template>
  <div id="app">
    <Toolbar></Toolbar>
    <router-view/>
    <Footer></Footer>
  </div>
</template>

<script>
  import Toolbar from "./components/Toolbar";
  import Footer from "./components/Footer";

  export default {
    components: {
      Footer,
      Toolbar
    }
  };
</script>

<style>
  body {
    padding: 0;
    margin: 0;
    font: 14px "Lucida Grande", Helvetica, Arial, sans-serif;
    overflow-x: hidden;
    min-width: 420px;
    width: 100vw;
    position: absolute;
    top: 0;
    bottom: 0;
    height: auto;
  }

  a {
    text-decoration: none;
  }

</style>
