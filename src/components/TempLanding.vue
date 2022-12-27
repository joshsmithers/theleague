<template>
  <body>
    <h2>
    Welcome
    </h2>

  <div class="column">
    <p>
    to the future home of
    </p>

    <img class="icon" src="../assets/theLeague.jpg">
  </div>
  </body>
  <div class="footer">
    THE LEAGUE | EST. 2013
  </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

h2 {
  align-self: flex-start;
  padding: 2rem 2rem;
  font-size: 3rem;
}

.column {
  align-self: center;
  display: flex;
  flex-direction: column;

}

.column p {
  margin: 0 0 5rem 0;
  font-size: 1.5rem;
}

.icon {
  width: 50%;
  align-self: auto;
}

.footer {
  display: flex;
  margin-top: auto;
}
</style>