<template>
  <div>
    <p></p>
  </div>
</template>

<script>
export default {
  name: 'Personajes',
  data() {
    return {
      personajes: [
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
</style>
