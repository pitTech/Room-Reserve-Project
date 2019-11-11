<template>
    <div>
<div id="grid-container">
        <div>
            I-1
        </div>
        <div>
            I-2
        </div>
        <div>
            I-3
        </div>
        <div>
            I-4
        </div>
        <div>
            I-5
        </div>
        <div>
            I-6
        </div>
        <div>
            I-7
        </div>
        <div>
            I-8
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