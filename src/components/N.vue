<template>
    <div>
<div id="grid-container">
        <div>
            N-1
        </div>
        <div>
            N-2
        </div>
        <div>
            N-3
        </div>
        <div>
            N-4
        </div>
        <div>
            N-5
        </div>
        <div>
            N-6
        </div>
        <div>
            N-7
        </div>
        <div>
            N-8
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