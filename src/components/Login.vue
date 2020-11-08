<template>
  <div class="Login">
    <form>
      <button @click.prevent="changeColor">Login</button>
    </form>
  </div>  
</template>
<script>
export default {
  methods: {
    changeColor(){
      document.querySelector('.home').style = 'background-color: green;'
    }
  },
}
</script>

<style>
  .Login{
    margin: auto;
  }
</style>