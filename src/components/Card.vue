<template>
    
    <div class="cardContainer">

        <div class="cardImg">

            <img :src="cardObject.thumb" :alt="cardObject.series">

        </div>

        <div class="cardTitle">{{ cardObject.series }}</div>

    </div>

</template>

<script>
    export default {
        
        name: "Card",
        props: ["cardObject"]
    
    };
</script>

<style scoped lang="scss">

    .cardContainer{

        height: 130px;
        width: calc( 100% / 6 );
        margin: 30px 10px;
        cursor: pointer;
                
        .cardImg{

            height: 100%;
            margin-bottom: 10px;
            overflow: hidden;


            img{

                height: 200px;

            }

        }

        .cardTitle{

                    
            width: 100%;
            font-size: 12px;
            text-transform: uppercase;

        }

    }

</style>