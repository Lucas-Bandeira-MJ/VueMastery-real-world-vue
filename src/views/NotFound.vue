<template>
  <div>
    <h1>Oops!</h1>
    <p>The {{ resource }} you're looking for is not here!</p>
    <router-link :to="{ name: 'event-list' }">Home</router-link>
  </div>
</template>

<script>
export default {
  props: {
    resource: {
      type: String,
      required: true
    }
  }
}
</script>

<style></style>
