<template>
    
    <div class="background">

        <div class="content"> 
            
            <span> --> Content goes here -- </span> 
                
        </div>

    </div>

</template>

<script>
    export default {
        
        name: "Content",
    
    };
</script>

<style scoped lang="scss">

    .background{

        background-color: black;
        height: 100px;
        width: 100%;
        display: flex;
        justify-content: left;
        align-items: center;

        .content{

            width: 70%;
            margin: auto;
            color: white;
            font-size: 25px;

        }

    }

</style>