<template>
    <div>
        <ul>
            <a href="">
                <li>
                     <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                     <span>DIGITAL COMICS</span>
                </li>
            </a>
            <a href="">
                <li>
                     <img src="../assets/img/buy-comics-merchandise.png" alt="">
                     <span>DC MERCHANDISE</span>
                </li>
             </a>
            <a href="">
                <li>
                     <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                     <span>SUBSCRIPTION</span>
                </li>
            </a>
            <a href="">
                <li>
                     <img src="../assets/img/buy-comics-shop-locator.png" alt="" class="shop">
                     <span>COMIC SHOP LOCATOR</span>
                </li>
            </a>
            <a href="">
                <li>
                     <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                     <span>DC POWER VISA</span>
                </li>
            </a>
        </ul>

    </div>
    
</template>

<script>

</script>

<style lang="scss" scoped>
    div {
        background-color: #0282F9;
        width: 100%;
        height: 10em;
        display: flex;
        justify-content: center;
    }
        ul{
            display: flex;
            list-style: none;
            justify-content: center;
            align-items: center;
             a {
                    text-decoration: none;
                }
            li {
                padding: 2em ;
                display: flex;
                align-items: center;
                img {
                    width: 40px;
                }
                span {
                    color: white;
                    font-size: 13px;
                    margin-left:0.5em
                }
            }
            
        }
        .shop {
            width: 28px;
        }
        

</style>