<template>
    <div>
        <h1 id="Size">Room Reserve</h1>
    <div id="grid-container">
        <div>
            A-1
        </div>
        <div>
            A-2
        </div>
        <div>
            A-3
        </div>
        <div>
            A-4
        </div>
        <div>
            A-5
        </div>
        <div>
            A-6
        </div>
        <div>
            A-7
        </div>
        <div>
            A-8
        </div>
        </div>
        <br>
        <B/>
            
    </div>
    

    
</template>

<script>
import B from './B'
    export default {
        name:"A",  
        components:{
            B
        }  
    }
</script>

<style >
#grid-container {
  display: grid;
  grid-template-columns:auto auto auto auto auto auto auto auto;
  grid-gap: px;
  color: black(3, 0, 165);
  padding: px;
  
}

#grid-container > div {
  background-color:whitesmoke;
  border: 1px solid black;
  text-align: center;
  font-size: 40px;
  
}
#Size{
    font-size: 55px;
}
</style>