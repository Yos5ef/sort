### 冒泡排序

```javascript
let arr = [1,124,5,121,5,231,212,5,1,12,3];
for (let i = 0, len= arr.length; i < len; i++) {
  for (let j = i; j < len ; j++) {
    if (arr[i] > arr[j]) [arr[i], arr[j]] = [arr[j], arr[i]];
  }
}
console.log(arr);
```
