<script setup>
  defineProps({
    title: String,
    price: Number,
    isAdded: Boolean
  });
</script>

<template>
  <div class="prod">
    <h2>Товар: {{title}}</h2>
    <h3>Цена: {{price}}</h3>
    <h3>IsAdded: {{isAdded}}</h3>
  </div>
</template>

<style scoped>
.prod {
  border: 1px solid black;
  padding: 10px;
  margin-bottom: 10px;
}
</style>