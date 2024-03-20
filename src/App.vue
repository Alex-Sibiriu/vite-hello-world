<script>
  export default {
    data() {
      return {
        title: 'Hello World',
        text: 'Spero che oggi ti porti gioia, ispirazione e nuove opportunità per crescere e prosperare'
      }
    }
  }
</script>

<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ text }}</p>
  </div>
</template>

<style scoped>
  div {
    text-align: center;
  }
  
  h1 {
    font-size: 7rem;
    cursor: pointer;
    color: chocolate;
    transition: all .5s;
  }

  h1:hover {
    font-size: 10rem;
    color: coral;
    text-shadow: 5px 5px 5px black;
  }

  p {
    font-size: 2rem;
    font-weight: bold;
    cursor: pointer;
    transition: all .5s;
  }

  p:hover {
    font-size: 2.5rem;
    color:darkorange;
    text-shadow: 2px 2px 2px black;
  }
</style>
