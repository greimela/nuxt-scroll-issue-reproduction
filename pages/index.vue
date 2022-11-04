<script setup>
const items = Array.from(Array(200).keys());
</script>
<template>
  <div>
    Scroll down, then navigate to page two. It should scroll to top, but it does
    not.
    <ul>
      <li v-for="item in items">
        {{ item }}. <NuxtLink to="/page2">Navigate to page 2</NuxtLink>
      </li>
    </ul>
  </div>
</template>
