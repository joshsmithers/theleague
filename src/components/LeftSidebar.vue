<template>
  <div class="left-column">
    <img class="top-left-icon" src="../assets/theLeague.jpg">
  </div>
</template>

<script>
export default {
  name: "LeftSidebar"
}
</script>

<style scoped>

.left-column {
  display: flex;
  flex-direction: column;
  height: 100vh;
  width: 200px;
  background-color: #3f3f3f;
}

.top-left-icon {
  margin: 10%;
  width: 80%;
  align-self: auto;
  border-radius: 25px;
}

</style>