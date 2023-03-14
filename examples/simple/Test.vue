<template>
  <h1>Hello World</h1>
  <button @click="isNotShow = !isNotShow">Toggle Message</button>
  <div v-if="isNotShow" class="message">{{ message }}</div>
</template>
<script>
export default {
  data: () => ({
    isNotShow: false,
    message: 'Great to be here!',
  }),
};
</script>
<style scoped>
.message {
  color: red;
}
</style>
