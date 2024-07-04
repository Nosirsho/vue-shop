<script setup>
import TheCard from './TheCard.vue'
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <TheCard
      title="Мужские кроссовки зеленые Nike"
      :price="1205"
      image-url="/sneakers/sneakers-1.jpg"
      :is-added="true"
      :is-favorite="true"
    />
    <TheCard image-url="/sneakers/sneakers-2.jpg" />
    <TheCard image-url="/sneakers/sneakers-3.jpg" />
    <TheCard image-url="/sneakers/sneakers-4.jpg" />
    <TheCard image-url="/sneakers/sneakers-5.jpg" />
    <TheCard image-url="/sneakers/sneakers-6.jpg" />
    <TheCard image-url="/sneakers/sneakers-7.jpg" />
    <TheCard image-url="/sneakers/sneakers-8.jpg" />
    <TheCard image-url="/sneakers/sneakers-9.jpg" />
    <TheCard image-url="/sneakers/sneakers-10.jpg" />
    <TheCard image-url="/sneakers/sneakers-11.jpg" />
    <TheCard image-url="/sneakers/sneakers-12.jpg" />
    <TheCard image-url="/sneakers/sneakers-1.jpg" />
    <TheCard image-url="/sneakers/sneakers-11.jpg" />
    <TheCard image-url="/sneakers/sneakers-12.jpg" />
    <TheCard image-url="/sneakers/sneakers-8.jpg" />
  </div>
</template>
