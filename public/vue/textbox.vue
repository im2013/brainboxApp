<template>
  <div>
    <label for="niceTextBox">Nicer Text Box:</label>
    <input
      type="text"
      class="form-control"
      id="niceTextBox"
      v-model="textBoxValue"
      placeholder="Enter text..."
    />
  </div>
</template>

<script>
export default {
  data() {
    return {
      textBoxValue: '',
    };
  },
};
</script>

<style scoped>
/* Add any custom styles if needed */
</style>