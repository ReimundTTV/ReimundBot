<template>
  <div class="home">
    <Apresentacao/>
    <Login/>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from '@/components/Login.vue'
import Apresentacao from '@/components/Apresentacao.vue'

export default {
  name: 'Home',
  components: {
    Login,
    Apresentacao
  }
}
</script>

<style>
  body{
    background-color: #090909;
  }

  .home{
        background-color: rgb(161, 2, 2);
        padding: 10px;
        border-radius: 5px;
        border: solid 1px white;
        color: white;
        width: 600px;
        margin: auto;
  }
</style>
