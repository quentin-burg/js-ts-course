---
layout: center
---

<h1 class="text-6xl">Awesome Javascript</h1>

---
class: p-4
---


# Arrays

Les [Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) sont très utiles en Javascript, les données peuvent être hétérogènes et ils peuvent être redimensionner.\
Il y a également beaucoup de méthodes utilitaires associées aux arrays, qui permettent de ne pas devoir parcourir les arrays avec un for ou un while


```ts {monaco-run}
const dumbArray = [1, 2, 3, 4, 5];

// Map
const doubleDumbArray = dumbArray.map(element => element * 2);


// Reduce
const sumOfDumbArray = dumbArray.reduce((acc, current) => {
  return acc + current;
}, 0);

console.log("🚀 ~ doubleDumbArray:", doubleDumbArray)
console.log("🚀 ~ sumOfDumbArray ~ sumOfDumbArray:", sumOfDumbArray)
```
