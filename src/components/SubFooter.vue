<template>
    <div>
        <div>
            <span>SiGN UP NOW</span>
        </div>
        <div>
            <ul class ="social">
                <li>FOLLOW US</li>
                <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                <li><img src="../assets/img/footer-youtube.png" alt=""></li>
                <li><img src="../assets/img/footer-periscope.png" alt=""></li>
            </ul>
        </div>

    </div>
    
</template>

<script>

</script>

<style lang="scss" scoped>
    div {
        width: 100%;
        height: 5em;
        background-color: #303030;
        position: sticky;
        display: flex;
        justify-content: space-around;
        align-items: center;
        div ul {
            list-style-type: none;
            display: inline-block;
        }
        div span {
            border: 1px solid #11518D;
            padding:1em;
            color: white;
            font-weight: bold;
        }
    }
    .social {
        display: flex;
        align-items: center;
    }
    .social li {
        padding-right: 1em;
    }

    .social:first-child {
        color: #11518D ;
        font-weight: bold;
    }

</style>