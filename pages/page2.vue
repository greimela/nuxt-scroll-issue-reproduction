<script setup>
const items = Array.from(Array(200).keys());
</script>
<template>
  <div>
    This is another page
    <ul>
      <li v-for="item in items">
        {{ item }}. <NuxtLink to="/">Navigate to page 1</NuxtLink>
      </li>
    </ul>
  </div>
</template>
