<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Siema!
  <br>
  <button @click="increase">Increase</button>
    {{ licznik }}
  </main>
</template>

<script>
export default {
    data() {
      return {
        licznik: 0
      }
    },
    methods: {
      increase() {
        this.licznik++
      }
    }
  }
</script>
