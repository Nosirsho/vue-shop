<script setup>
import TheHeader from './components/TheHeader.vue'
import CardList from './components/CardList.vue'
import TheDrawer from './components/TheDrawer.vue'
</script>

<template>
  <!-- <TheDrawer/> -->
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <TheHeader />
    <div class="p-10">
      <div class="flex justify-between items-center">
        <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>

        <select class="py-2 px-3 border rounded-md outline-none" name="" id="">
          <option value="">1</option>
          <option value="">2</option>
          <option value="">3</option>
        </select>
        <div class="relative">
          <img class="absolute left-4 top-3" src="/search.svg" alt="Search">
          <input class="border rounded-md py-2 pl-11 pr-4 outline-none focus:border-gray-400" type="text" placeholder="Search...">
        </div>
      </div>
      <CardList />
    </div>
  </div>
</template>
