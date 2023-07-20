<script>
export default {
    methods: {
        sayHello: function (event) {
        alert('Hello !')
    },
  }
}
</script>

<template>
    <header class="header" @click="sayHello">
      Accueil Services Contact
    </header>
</template>

<style scoped>
.header {
    background-color: blue;
}
</style>