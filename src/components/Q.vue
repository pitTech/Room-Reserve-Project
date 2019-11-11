<template>
    <div>
<div id="grid-container">
        <div>
            Q-1
        </div>
        <div>
            Q-2
        </div>
        <div>
            Q-3
        </div>
        <div>
            Q-4
        </div>
        <div>
            Q-5
        </div>
        <div>
            Q-6
        </div>
        <div>
            Q-7
        </div>
        <div>
            Q-8
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