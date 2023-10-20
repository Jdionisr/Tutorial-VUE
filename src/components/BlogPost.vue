<script setup>
defineProps(["title", "id", "body", "colorText"]);
</script>

<template>
  <div class="card">
    <div class="card-body">
      <h5 class="card-title" :class="`text-${colorText}`">
        {{ id }} - {{ title }}
      </h5>
      <h6 class="card-subtitle">{{ body }}</h6>
      <p>Lorem ipsum dolor sit amet.</p>
    </div>
  </div>
</template>
