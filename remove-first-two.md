Use destructuring assignment with the rest operator to perform an effective `Array.prototype.slice()` so that arr is a sub-array of the original array source with the first two elements omitted.

```js
const source = [1,2,3,4,5,6,7,8,9,10];

function removeFirstTwo(list) {
  // your code goes here
}

const arr = removeFirstTwo(source);
console.log(arr); // should be [3,4,5,6,7,8,9,10]
console.log(source); // should be [1,2,3,4,5,6,7,8,9,10];
```
[Solution](https://gist.github.com/sandrabosk/d80e17e2ebeed01d4b07b9b27ead5b36)