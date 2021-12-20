<template>
    
    <div class="background">

        <div class="containerPreFooter">

            <div class="preFooterLink">

                <div>

                    <div class="preFooterLinkContainer">
                    
                    <span>DC Comics</span>

                    <ul>

                        <li>Characters</li>

                        <li>Comics</li>

                        <li>Movies</li>

                        <li>TV</li>

                        <li>Games</li>

                        <li>Videos</li>

                        <li>News</li>

                    </ul>
                    
                </div>

                <div class="preFooterLinkContainer">

                    <span>Shop</span>

                    <ul>

                        <li>Shop DC</li>

                        <li>Shop DC Collectibles</li>

                    </ul>

                </div>

                </div>

                <div class="preFooterLinkContainer">
                    
                    <span>DC</span>

                    <ul>

                        <li>Terme Of Use</li>

                        <li>Privacy policy (New)</li>

                        <li>Ad Choices</li>

                        <li>Advertising</li>

                        <li>Jobs</li>

                        <li>Subscriptions</li>

                        <li>Talent Workshops</li>

                        <li>CPSC Certificates</li>

                        <li>Ratings</li>

                        <li>Shop Help</li>

                        <li>Contact Us</li>

                    </ul>
                    
                </div>

                <div class="preFooterLinkContainer">
                    
                    <span>Sites</span>

                    <ul>

                        <li>DC</li>

                        <li>MAD Magazine</li>

                        <li>DC Kids</li>

                        <li>DC Universe</li>

                        <li>DC Power Visa</li>

                    </ul>
                    
                </div>

            </div>

            <div class="preFooterImage">

                <img src="../../img/dc-logo-bg.png" alt="">

            </div>

        </div>

    </div>

</template>

<script>
    export default {
        
        name: "PreFooter",
    
    };
</script>

<style lang="scss" scoped>

    .background{

        background-image: url("../../img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        height: 400px;
        width: 100%;

        .containerPreFooter{
            
            height: 100%;
            width: 70%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            overflow: hidden;

            .preFooterLink{

                display: flex;
                justify-content: center;
                align-items: start;
                padding: 10px 0;

                .preFooterLinkContainer{

                    display: flex;
                    flex-direction: column;
                    margin: 0 20px;

                    span{

                    color: white;
                    font-weight: bold;
                    margin-bottom: 10px;
                    font-size: 20px;
                    text-transform: uppercase;

                    }

                    ul{

                        margin-bottom: 20px;

                        li{

                            list-style-type: none;
                            color: gray;
                            margin: 5px 0;

                        }

                    }

                }

            }

            .preFooterImage{

                height: 100%;
                display: flex;
                align-items: center;


                img{

                    height: 150%;

                }

            }

        }

    }

</style>