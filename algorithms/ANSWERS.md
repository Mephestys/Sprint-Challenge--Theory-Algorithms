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

b) Start by dropping an egg from the middle floor (or if the floors are even numbered, start from the lowest of the upper floors, i.e. in a building of 4 floors, start from floor 3). If the egg breaks, move down to the middle floor of the remaining lower floors, otherwise if it does not break, move to the middle floor of the remaining upper floors. Continue until reaching the one floor where the egg does not break, but does break from the floor just above it.

Basically a binary search tree.

## Exercise III.

a) Best-case scenario, with no repeating elements, the running time should be O(n). In the worst case, O(n<sup>2</sup>).

b) This would become a divide-and-conquer approach, meaning the run time should be O(log<sub>2</sub>(n)).