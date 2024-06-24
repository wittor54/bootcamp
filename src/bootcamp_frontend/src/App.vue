<script setup>
</script>

<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h1>Hello, World!</h1>
    <h1>{{ num }}</h1>
    <button @click="add">+</button>
    <button @click="subtract">-</button>
  </main>
</template>

<script>
export default {
  data() {
    return {
      num: 0      
    }
  },
  methods: {
    add() { this.num++ },
    subtract() { this.num-- },
  }
}

</script>