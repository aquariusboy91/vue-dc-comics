<template>
    <div class ="container-cards">
         <img
            :src="img" 
    >
        <span>{{series}}</span>
        <span>{{price}}</span>
    </div>
  
</template>

<script>
export default {
     name: "CardsMain",
     props: ['img', 'price', 'series', 'type'],
     
}
</script>

<style lang="scss">
    .container-cards {
      flex-basis: calc((100% / 6) - 1em);
      display: flex;
      flex-direction: column;
      background-color: black;
      align-items: center;
      img {
        width: 80%;
        height: 80%;
      }
      span {
          font-size: 13px;
          color: white;
          font-weight: bold;
          padding-top: 0.5em ;
      }
    }

</style>