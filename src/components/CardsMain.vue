<template>
    <div>
         <img
            :src="img" 
    >
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
    .product {
      flex-basis: calc((100% / 4) - 0.4em);
      margin: 0.2em;
      padding: 1em;
      background-color: white;
      img {
        width: 100%;
      }
    }

</style>