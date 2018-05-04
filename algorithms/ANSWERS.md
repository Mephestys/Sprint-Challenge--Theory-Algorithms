## Exercise I.

a) O(n)

b) O(log n)

c) O(sqrt(n))

d) O(n log n)

e) O(n^3)

f) O(n)

g) O(n)

## Exercise II.

a) 
```js
const maxDiff = (arr) => {
  let min = arr[0];
  let max = arr[0];

  for (let i = 0; i < arr.length; i++) {
    let val = arr[i];

    if (val < min) min = val;
    if (val > max) max = val;
  }
  return max - min;
}
```

b)

## Exercise III.

a)

b)