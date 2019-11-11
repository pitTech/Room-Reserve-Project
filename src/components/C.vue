<template>
    <div>
<div id="grid-container">
        <div>
            C-1
        </div>
        <div>
            C-2
        </div>
        <div>
            C-3
        </div>
        <div>
            C-4
        </div>
        <div>
            C-5
        </div>
        <div>
            C-6
        </div>
        <div>
            C-7
        </div>
        <div>
            C-8
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