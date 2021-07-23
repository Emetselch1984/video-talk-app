<template>
  <div id="hello">
    <v-app>
      <p class="red">{{ message }}</p>
    </v-app>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
