<template>
    <div class="container">
        <div class="cont-list">
            <div>
                <ul>
                    <li>
                        <span>DC COMICS</span>
                    </li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li>
                        <span>Shop</span>
                    </li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div>
                <ul>
                    <li>
                        <span>DC COMICS</span>
                    </li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
             <div>
                <ul>
                    <li>
                        <span>DC COMICS</span>
                    </li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
        </div>
        <div><img src="../assets/img/dc-logo-bg.png" alt=""></div>

        
        
    </div>
    
</template>

<script>

</script>

<style lang="scss" scoped>
    .container {
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        width: 100%;
        height: 25em;
        display: flex;
        justify-content: space-around;
        align-items: center;
        ul {
            list-style: none;
            color: grey;
            font-size: 12px;
            padding-bottom: 1em;
            li span {
                color: white;
                margin-bottom: 2em;
            }
        }
            li {
                line-height: 1.8em;
            }
        ul li:first-child{
            font-size: 22px;
            padding-right: 1em;
        }
        
    }
    .cont-list {
        display: flex;
    }
    img {
        width: 80%;
    }

</style>