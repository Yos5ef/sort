#### 维基百科
```javascript
Array.prototype.merge_sort = function() {
  var merge = function(left, right) {
    var final = [];
    while (left.length && right.length)
      final.push(left[0] <= right[0] ? left.shift() : right.shift());
    return final.concat(left.concat(right));
  };
  var len = this.length;
  if (len < 2) return this;
  var mid = len / 2;
  return merge(this.slice(0, parseInt(mid)).merge_sort(), this.slice(parseInt(mid)).merge_sort());
};
console.log([123,14,1,454,1,3124,125,6,1,312,65,22].merge_sort());
```
