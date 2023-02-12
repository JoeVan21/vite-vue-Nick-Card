<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

img{
  max-width: 400px;
}
button {
  cursor:pointer;
  margin: 1px;
  border: 2px dashed blue;
  color:#00FFFF; 
  background-color: black;
  border-radius:20px;
 text-transform: uppercase;
padding: 8px 8px;
}
.card {
  font-size: 15px;
  margin: 5px;
  padding: 10px;
  text-align:center;
  border: solid blue 10px;
  padding: 8px;
  max-width: 400px;
}
.borders {
 justify-content:center;
  display:flex;
}
button:hover{
  background-color: #0400FE;
}

button:focus{
  background-color: #0400FE;
}


@media screen and (min-width:501px) and (max-width:800px) {

}
@media screen and (max-width:500px) {
  .card{
    font-size: 3vw
  }
  
</style>
