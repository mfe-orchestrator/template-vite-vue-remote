<script setup lang="ts">
import { ref } from 'vue'

const state = ref(0)
</script>

<template>
  <div>
    <button id="click-btn" class="shared-btn" @click="state++">
      Click me: {{ state }}
    </button>
  </div>
</template>

<style scoped>
.shared-btn {
  border-radius: 8px;
  border: 1px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  color: #ffffff;
  cursor: pointer;
  transition: border-color 0.25s;
}

.shared-btn:hover {
  border-color: #646cff;
}
</style>
