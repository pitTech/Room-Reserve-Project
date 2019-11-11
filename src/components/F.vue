<template>
    <div>
<div id="grid-container">
        <div>
            F-1
        </div>
        <div>
            F-2
        </div>
        <div>
            F-3
        </div>
        <div>
            F-4
        </div>
        <div>
            F-5
        </div>
        <div>
            F-6
        </div>
        <div>
            F-7
        </div>
        <div>
            F-8
        </div>
        </div>
    </div>
</template>

<script>
    export default {
        
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