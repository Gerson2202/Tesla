
<template>

    <div>
        <h1 style="margin-toh1:200px;text-align:center">Todo list</h1>
        
        <div class="todoListContainer">       
        <add-item-form/>
        

        </div>
    </div>
    
</template>


<script>

// componentes creados
import AddItemForm from "../components/addItemForm.vue"
import listItem from "../components/listItem.vue"
import listView from "../components/listView.vue"


export default {

    // IMPORTAMOS LOS COMPONENTES QUE CREAMOS PARA PODER MOSTRARLOS ACA

   components:{
       AddItemForm,
       listItem,
       listView
   },
    
    data(){
        return {
            
        }
    }
}
</script>

<style scoped>

  .todoListContainer{
    width: 400px;
    margin: auto;
    margin-top: 50px;
  }

</style>