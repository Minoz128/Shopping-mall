<template>
    <div id="app">
      {{ message }}
      <input v-model="message"/>
    </div>
</template>

<script>
    new Vue( {
      el: "#app",
      data:{
        message:"Hello Minoz!"
      }
    })
</script>

<style scoped>

</style>
