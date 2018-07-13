### 插入排序
```javascript
let arr = [8, 4, 2, 9, 3];
for (let i = 1, len = arr.length; i < len; i++) {
  let num = i;
  for (let j = i; j >=0; j --) {
    if (arr[j] > arr[num]) {
      [arr[j], arr[num]] = [arr[num], arr[j]];
      num = j;
    }
  }
}
console.log(arr);
```
