<template>
  <div>
    <div v-for="(item, index) in caracteres" :key="index">
      <img :src="item.image" :alt="item.name"> {{item.name}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'Personajes',
  data() {
    return {
      caracteres: [
        {
          name: "Rick Sánchez",
          image: "https://rickandmortyapi.com/api/character/avatar/1.jpeg",
        },
        {
          name: "Morty Smith",
          image: "https://rickandmortyapi.com/api/character/avatar/2.jpeg",
        },
        {
          name: "Summer Smith",
          image: "https://rickandmortyapi.com/api/character/avatar/3.jpeg",
        },
        {
          name: "Beth Smith",
          image: "https://rickandmortyapi.com/api/character/avatar/4.jpeg",
        },
        {
          name: "Jerry Smith",
          image: "https://rickandmortyapi.com/api/character/avatar/5.jpeg",
        },
      ]
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img {
    height: 150px;
    border-radius: 50%;
    margin: 20px 10px 20px 40px;
  } 
</style>
