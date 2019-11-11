<template>
    <div>
<div id="grid-container">
        <div>
            B-1
        </div>
        <div>
            B-2
        </div>
        <div>
            B-3
        </div>
        <div>
            B-4
        </div>
        <div>
            B-5
        </div>
        <div>
            B-6
        </div>
        <div>
            B-7
        </div>
        <div>
            B-8
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