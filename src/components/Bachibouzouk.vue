<script>
export default {
  data: function () {
    return {
      awesome: true,
      name: "Jean-Paul"
    }
  }
}
</script>

<template>
    <footer v-if="awesome">
        Copyright 2023 {{name}}
    </footer>
    <footer v-else>
        Copyright autre
    </footer>
</template>