<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h1>Cześć</h1>
  </br>
  <button @click="podbij">podbij</button>
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
    podbij() {
      this.licznik++
    }
  }
}
</script>