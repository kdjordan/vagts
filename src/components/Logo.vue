<template>
  <div class="logo">
    <img alt="Vue logo" src="../assets/img/logo.svg">
   </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.logo {
  display: flex;
  height: 100vh;
  width: 50vw;
  align-content: center;
  justify-content: center;
}

.logo img  {
  height: 100px;
}

</style>
