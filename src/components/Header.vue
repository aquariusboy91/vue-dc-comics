<template>
    <div class="header">
        <img src="../assets/img/dc-logo.png" alt="" class="logo">
        <ul>
            <a href=""><li>Characters</li></a>
            <a href=""><li>Comics</li></a>
            <a href=""><li>Movies</li></a>
            <a href=""><li>Tv</li></a>
            <a href=""><li>Games</li></a>
            <a href=""><li>Collectibles</li></a>
            <a href=""><li>Videos</li></a>
            <a href=""><li>Fans</li></a>
            <a href=""><li>News</li></a>
            <a href=""><li>Shop</li></a>
        </ul>
    </div>
    
</template>

<script>

</script>

<style lang="scss" scoped>
 ul {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    a li {
      display: block;
      text-decoration: none;
      padding: 1em;
      color:black;
      font-size: 13px;
      font-weight: bold;
    }
    a {
      text-decoration: none;
    }
  }
  .logo {
    width: 70px;
    height: 70px;
  }
  .header {
    display: flex;
    justify-content: space-around;
    height: 7em;
    align-items: center;
  }
</style>


