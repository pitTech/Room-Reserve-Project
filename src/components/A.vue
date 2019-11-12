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
        <br>
         <C/>
         <br>
         <D/>
         <br>
         <E/>
         <br>
         <F/>
         <br>
         <G/>
         <H/>
         <br> 
         <I/>
         <br>
         <J/>
         <br>
         <K/>
         <br>
         <L/>
         <br>
         <M/>
         <br>
         <N/>
         <br>
         <O/>
         <br>
         <P/>
         <br>
         <Q/>
         <br>
         <R/>   
    </div>
    

    
</template>

<script>
import B from './B'
import C from './C'
import D from './D'
import E from './E'
import F from './F'
import G from './G'
import H from './H'
import I from './I'
import J from './J'
import K from './K'
import L from './L'
import M from './M'
import N from './N'
import O from './O'
import P from './P'
import Q from './Q'
import R from './R'
    export default {
        name:"A",  
        components:{
            B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R
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