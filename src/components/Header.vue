<template>

    <header>

        <div class="logo">

            <img src="../../img/dc-logo.png" alt="">

        </div>

        <div class="header-list">

            <ul>

                <li>Characters</li>

                <li>Comics</li>

                <li>Movies</li>

                <li>TV</li>

                <li>Games</li>

                <li>Collectibles</li>

                <li>Videos</li>

                <li>Fans</li>

                <li>News</li>

                <li>Shop</li>

            </ul>

        </div>

    </header>

</template>

<script>
    export default {
        
        name: "Header",
    
    };
</script>

<style scoped lang="scss">

    header{

        height: 100px;
        width: 70%;
        margin: auto;
        background-color: white;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .logo{

            height: 70%;
            width: auto;
            display: flex;
            align-items: center;

            img{

                height: 100%;

            }

        }

        .header-list{
            
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


                    &:hover{

                        color: #0282f9;
                        border-bottom: 5px solid #0282f9;

                    }

                }

            }

        }

    }

</style>
