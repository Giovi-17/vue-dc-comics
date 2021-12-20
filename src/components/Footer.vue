<template>
    
    <footer>

        <div class="footer-container">

            <div class="sign-up">

                Sign-up Now!

            </div>

        <div class="footer-list">

            <ul>

                <li>Follow Us</li>

                <li><img src="../../img/footer-facebook.png" alt=""></li>

                <li><img src="../../img/footer-twitter.png" alt=""></li>

                <li><img src="../../img/footer-youtube.png" alt=""></li>

                <li><img src="../../img/footer-pinterest.png" alt=""></li>

                <li><img src="../../img/footer-periscope.png" alt=""></li>

            </ul>

        </div>

        </div>

    </footer>

</template>

<script>
    export default {
        
        name: "Footer",
    
    };
</script>

<style scoped lang="scss">

    footer{

        height: 100px;
        width: 100%;
        background-color: #303030;
        

        .footer-container{

            width: 70%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;

            .sign-up{

            height: 100%;
            width: auto;
            display: flex;
            align-items: center;
            color: white;
            text-transform: uppercase;
            border: 2px solid #0282f9;
            font-weight: bold;
            padding: 10px;

            img{

                height: 70%;

            }

        }

        .footer-list{
            
            ul{

                display: flex;
                height: 100px;
                line-height: 100px;
                align-items: center;
                
                li{
                    
                    height: 100%;
                    list-style-type: none;
                    margin: 15px;
                    text-transform: uppercase;
                    font-weight: bold;
                    color: #0282f9;
                    display: flex;
                    justify-content: center;
                    align-items: center;

                    img{

                        height: 30%;

                    }

                }

            }

        }

        }

    }

</style>
