<template>
  <div class="panel-layout">
  <div class="left-column">
    <img class="top-left-icon" src="../assets/theLeague.jpg">
  </div>
  </div>

  <div class="footer">
    THE LEAGUE | EST. 2013
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

.panel-layout {
  display: flex;
  height: 100%;
  width: 100%;
  background-color: #3f5f5f;
  overflow: hidden;
}

.left-column {
  display: flex;
  flex-direction: column;
  height: 100vh;
  width: 200px;
  background-color: #3f3f3f;
}

.column p {
  margin: 0 0 5rem 0;
  font-size: 1.5rem;
}

.top-left-icon {
  margin: 10%;
  width: 80%;
  align-self: auto;
  border-radius: 25px;
}

.footer {
  display: flex;
  margin-top: auto;
}
</style>