  
<template>
  <div>
    <h2>Enter Text</h2>
    <input v-model="message" placeholder="enter text" />
    <p>Converted text: {{ message.toUpperCase() }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "",
    };
  }
};
</script>

<style scoped>
</style>