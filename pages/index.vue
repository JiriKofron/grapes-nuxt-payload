<script setup lang="ts">
import 'grapesjs/dist/css/grapes.min.css';
import grapesjs from 'grapesjs';

onMounted(() => {
  const editor = grapesjs.init({
    container: '#gjs',
    height: 600,
    width: '100%',
    // ... other options
  });
})
</script>

<template>
<div>
  <h1 class="text-red-400">index page</h1>
  <div id="gjs">
    What is this?
  </div>
</div>
</template>
