<script>
export default {
  data() {
    return {
      viteMessage: 'Hello Vite!!',
      vueMessage: 'Hi Vue!!'
    }
  }
}
</script>

<template>
  <div class="messages">
    <h2>{{ viteMessage }}</h2>
    <h2>{{ vueMessage }}</h2>
  </div>
</template>

<style>
h2 {
  font-size: 3rem;
}

h2:first-child {
  color: #737BFF;
}

h2:last-child {
  color: #43D392;
}
</style>
