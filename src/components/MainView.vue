<template>
  <div class="panel-layout">
    <LeftSidebar/>
  </div>

  <div class="footer">
    THE LEAGUE | EST. 2013
  </div>
</template>

<script setup lang="ts">

import LeftSidebar from "@/components/LeftSidebar.vue";

function getLeague(){
  const leagueId = 715986967640215552;

}




</script>

<style scoped>

.panel-layout {
  display: flex;
  height: 100%;
  width: 100%;
  background-color: #3f5f5f;
  overflow: hidden;
}

.footer {
  display: flex;
  margin-top: auto;
}
</style>