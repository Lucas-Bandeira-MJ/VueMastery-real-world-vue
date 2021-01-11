<template>
  <div>
    <h1>Uh-oh!</h1>
    <p>It looks like you're experiencing some conection problems.</p>
    <router-link :to="{ name: 'event-list' }">Home</router-link>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
