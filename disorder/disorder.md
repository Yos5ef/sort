```javascript
var arr = [1,2,3,4,5,6,7,8,9,0];
for(var i=arr.length;i;i--){
  let j = Math.floor(Math.random()*i);
  [arr[i-1],arr[j]]  = [arr[j],arr[i-1]]
}
console.log(arr);
```
