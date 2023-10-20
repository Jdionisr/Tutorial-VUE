<script setup>
import BlogPost from "./components/BlogPost.vue";
import ButtonCounter from "./components/ButtonCounter.vue";
</script>

<template>
  <div class="bg-body-tertiary">
    <h1>APP</h1>
    <ButtonCounter />
    <BlogPost title="Post 1" id="1" body="Description 1" colorText="primary" />
    <BlogPost
      title="Post 2"
      id="2"
      body="Description 2"
      colorText="secondary"
    />
    <BlogPost title="Post 3" id="3" body="Description 3" colorText="success" />
    <BlogPost title="Post 4" id="4" body="Description 4" colorText="info" />
  </div>
</template>

<style></style>
