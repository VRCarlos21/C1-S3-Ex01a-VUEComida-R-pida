
<script>

</script>

<template>
    
    <div >
        <img :src="url" alt="nombre">
            
        <h2>{{nombre}}</h2>
        <p>{{nombre1}}</p>             
        <a v-bind:href="url" target="_blank">{{nombre2}}</a> 
    </div>
    
</template>

<style scoped>
    div{
       width: 500px;
       height: 350px;
        display: inline;  
        text-align: center;
        border: 3px solid ;
        padding: 1%;
        border-radius: 30px;
        margin: 15px; 
    }
    img{
        width: 20rem;
        height: 10rem;
        padding: 0.5rem;
        background: snow;
    }
    a{
        text-decoration: none;
        color: snow;
        background: #DC143C;
        padding: 0.3rem;
        border-radius: 5px;
        border: solid 1px #f2f2f2;
    }
   
</style>

<script>
   
    export default{
        props: {
            url:{
                String,
            },
            nombre: {
                String,
            },
            nombre1: {
                String,
            },
            nombre2: {
                String,
            },
        },
        
    };
</script>