<template>
  <div class="footer-container">
    <div>Design + Dev + Art by Jeremy Hull</div>
    <div>Vue.js</div>
  </div>
</template>

<script>
  export default {
    name: "Footer"
  };
</script>

<style scoped>
  .footer-container {
    background: rgba(255, 255, 255, 0.4);
    font-style: italic;
    color: #333;
    position: fixed;
    pointer-events: none;
    bottom: 0;
    width: 100vw;
    padding: 0 10px;
  }

  .footer-container > div {
    display: inline-flex;
  }

  .footer-container > div:last-child {
    color: red;
  <!-- TODO: Need to fix this -->
  }


</style>
