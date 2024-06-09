<template>
  <div>
    <button v-on:click="sayHello">Click me</button>
  </div>
</template>

<script>
export default {
  methods: {
    sayHello() {
      alert('What\'s up?')
    }
  }
}
</script>
