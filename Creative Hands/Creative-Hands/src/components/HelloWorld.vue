<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Hemos dado los primeros pasos de Creative Hands\
      <br>
      <br>
      <a target="_blank" href="https://vitejs.dev/">Graffitis</a> 
      <br>
      <a target="_blank" href="https://vitejs.dev/">Urban Art</a> 
      <br>
      <a target="_blank" href="https://vitejs.dev/">Gallery</a> 
      <br>
      <a target="_blank" href="https://vitejs.dev/">Graffitis</a> 
      <br>
      <a target="_blank" href="https://vuejs.org/"></a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 900;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: center;
  }
}
</style>
