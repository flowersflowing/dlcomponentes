<template>
  <div>
    <div v-for="(item, index) in caracteres" :key="index" class="pers">
      <img :src="item.image" :alt="item.name"> <span>{{item.name}}</span>
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
    margin: 20px 30px 20px 40px;
  }
  .pers {
    display: flex;
    align-items: center;
  }
</style>
