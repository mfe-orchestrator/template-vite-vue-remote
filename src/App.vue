<script setup>
import Button from './components/Button.vue'
</script>

<template>
  <div class="App">
    <h1>Vite &amp; Vue</h1>
    <p>This is a remote microfrontend and here is the exposed button.</p>
    <div class="card">
      <Button />
      <p>
        Edit <code>src/components/Button.vue</code> and save to test HMR
      </p>
    </div>
    <p class="read-the-docs">
      This standalone page exists only for local development. The host application
      consumes <code>./Button</code> through <code>assets/remoteEntry.js</code>.
    </p>
  </div>
</template>
