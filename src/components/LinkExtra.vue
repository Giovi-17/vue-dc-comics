<template>
    
    <div class="background">

        <div class="containerLinkExtra">

            <ul>

                <li><img src="../../img/buy-comics-digital-comics.png" alt="">Digital Comics</li>

                <li><img src="../../img/buy-comics-merchandise.png" alt="">Dc Merchandise</li>

                <li><img src="../../img/buy-comics-subscriptions.png" alt="">Subscription</li>

                <li><img src="../../img/buy-comics-shop-locator.png" alt="">Comic Shop Locator</li>

                <li><img src="../../img/buy-dc-power-visa.svg" alt="">Dc Power Visa</li>

            </ul>

        </div>

    </div>

</template>

<script>
    export default {
        
        name: "LinkExtra",
    
    };
</script>

<style lang="scss" scoped>

    .background{

        background-color: #0282f9;
        width: 100%;
        height: 150px;

        .containerLinkExtra{

            width: 70%;
            height: 100%;
            margin: auto;

            ul{

                display: flex;
                justify-content: center;
                align-items: center;
                height: 100%;
                width: 100%;

                li{

                    height: 100%;
                    list-style-type: none;
                    margin: 0 25px;
                    text-transform: uppercase;
                    color: white;
                    display: flex;
                    justify-content: center;
                    align-items: center;

                    img{

                        height: 40%;
                        vertical-align: middle;
                        margin: 0 10px;

                    }

                }

            }

        }

    }

</style>