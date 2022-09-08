<template>
    <div>Nội dung của component Greeting {{ city }} {{ country }}</div>
</template>

<script>
  module.exports = {
    data: function () {
    return {
      city: 'Ha noi',
      country: 'Viet nam'
    }
  }
  }
</script>

<style scoped>
 div {
     color:red;
 }
</style>