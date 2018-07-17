```javascript
let arr = [123,12,423,3437,5679,780,7,54645,46,68,80,5,344,2];
let arr2 = [];
let arr3 = [];
for (let i = 0, len = arr.length; i < len; i++) {
   arr2[arr[i]] = arr[i];
}
for (let i = 0, len = arr2.length; i < len; i++) {
  if (arr2[i]) arr3.push(arr2[i]) 
}
console.log(arr3);
```
