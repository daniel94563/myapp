<template>
  <v-container>
  </v-container>
</template>

<script>

   var myData =[{
  "name": "Ian Devling",
  "imageUrl": "https://raw.githubusercontent.com/bumbeishvili/Ass…s/master/Projects/D3/Organization%20Chart/cto.jpg",
  "id": "O-1",
  "parentId": null
},
{
  "name": "Ian Devling",
  "imageUrl": "https://raw.githubusercontent.com/bumbeishvili/Ass…s/master/Projects/D3/Organization%20Chart/cto.jpg",
  "id": "O-2",
  "parentId": "O-1"
}];
var data = myData.map(d=>{
  return {
    'nodeId':d.id,
    "parentNodeId":d.parentId
  }


});

console.log(myData);
console.log(myData[1]);
console.log(data);
  export default {
    name: 'HelloWorld',


  }
</script>
