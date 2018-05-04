<template>
  <div class="toolbar">
    <div>
      <a href="http://twitter.com/coderado"
         target="_blank">
        <div v-html="twitter"></div>
      </a>
      <a href="http://www.linkedin.com/in/jeremyhull"
         target="_blank">L</a>
      <a href="http://github.com/jchull"
         target="_blank">G</a>
      <a href="http://codepen.io/coderado"
         target="_blank">C</a>
    </div>

  </div>
</template>


<script>

  import twitter from '@/components/social-icons/twitter.svg'

  export default {
    name: "Toolbar",
    props: {
      twitter: twitter
    }
  };
</script>


<style scoped>
  .toolbar {
    min-height: 24px;
    background-color: rgba(32, 42, 92, .8);
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    right: 0;
    bottom: auto;
    margin: 0;
  }

  img {
    width: 20px;
    height: 20px;
    margin: 5px;
    display: inline-block;
  }

  path {
    fill: #FFFFFF;
  }

</style>
