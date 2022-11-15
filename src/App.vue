<template>
  <div id="app">
    
    <label>name </label>
    <input type="text"  v-model="text1" placeholder="heyy"><br/>
    <br>
    <label>email </label>
    
    <input type="text"  v-model="text3" placeholder="email">
   <br>
   You name is : <b>{{ text1 }}</b><br>
   your email is : <b>{{ text3 }}</b><br>
    
  </div>
</template>

<script>


export default {
  
  name: 'App',
  
  components: {
    
  },
  data() {
    return {
      text1: '',
      text3:'',
    };
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
