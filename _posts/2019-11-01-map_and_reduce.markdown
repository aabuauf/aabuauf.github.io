---
layout: post
title:      ".map and .reduce"
date:       2019-11-01 17:22:24 +0000
permalink:  map_and_reduce
---

array.map and array.reduce. It was one of my confusing part.
Map:
It is doing the same as this function
```
function mapsample (array){
let newarray=[]
for (let i =0; i<array.length;i++){
newarray[i]=array[i]**2 //Add any operation
}
return newarray
}
```
instead of using this function `mapsample(array)` you can use .map like `array.map(function(num) {return num * 2})`


Same for reduce: 
```
function reducesample (array,startpoint=0){
let sum = startpoint
for (let i =0; i<array.length;i++){
sum= sum+ array[i]
}
return sum
}
```

instead of using this function `reducesample(array)` you can use .reduce like `array.reduce(function(total, num) {return total + num;})`

I hope that is useful and remove any confusion

