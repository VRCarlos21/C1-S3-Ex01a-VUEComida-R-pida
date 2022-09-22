<template>

  <h1>COMIDA RAPIDA-CARLOS ALEXIS VAZQUEZ ROSAS 3B</h1>
    
  <br>
  <card2 />
  <br>
  <card url="https://www.saborusa.com/wp-content/uploads/2019/10/Animate-a-disfrutar-una-deliciosa-pizza-de-salchicha-Foto-destacada.png" nombre="Pizza de Pepperoni" nombre1="Para satisfacer el hambre o antojo nada mejor que la Pizza de Pepperon" nombre2="Precio: $20"/>

    <card url="https://www.clarin.com/img/2021/06/17/LC25eDtCT_1200x630__1.jpg" nombre="Hamburguesa" nombre1="Hamburguesa sencilla con una mezcla de quesos cheddar,mozzarella y tocino." nombre2="Precio: $80"/>
    
    <card url="https://www.paulinacocina.net/wp-content/uploads/2017/10/frenchfries.jpg" nombre="Papas fritas" nombre1="Papas fritas crujientes de distintos tamaños como jumbo, grande y chicos" nombre2="Precio: $50"/>
    
    <card url="https://saboryestilo.com.mx/wp-content/uploads/2021/06/Hot-Dog-Street-Style-1200x675.jpg" nombre="Hod Dog" nombre1="Hot Dog americano de salchicha tocino, queso americano entre mas ingredientes" nombre2="Precio: $25"/>
    
    <card url="https://dam.cocinafacil.com.mx/wp-content/uploads/2019/01/Co%CC%81mo-hacer-banderillas.jpg" nombre="Banderilla" nombre1="Banderilla rellena de salchicha con ketchup, mostaza, mayoneza y entre otros." nombre2="Precio: $12"/>
   
    <card url="https://assets.unileversolutions.com/recipes-v2/236933.jpg" nombre="Spaguetti" nombre1=" Es un tipo de pasta italiana elaborada con harina de grano duro y agua." nombre2="Precio: $40"/>
   
    <br>
    <br>
    
    
</template>


<style>
  h1{
    text-align: center;
  }
</style>

<script>

 
  import Card from "./components/Card.vue"
  import Card2 from "./components/Card2.vue"
  import Card3 from "./components/Card3.vue"
  export default {
    
    components:{Card,Card2,Card3
    },
    
    

  };
</script>