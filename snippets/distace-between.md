---
title: Distance between two ponits
tags: array,intermediate
---

Function gets an bydimensional array with 2 coordinates and return de distance between them

- Takes two latitude and logintude arguments.
- Subtract the pairs and use multiplicate by itself
- Sum the result of the pairs and make squareroot of them
- Return the result

```js
const distanceBetween = coordinates =>
  {
  return Math.sqrt(Math.pow((coordinates[0][0] - coordinates[0][1]),2) + Math.pow((coordinates[1][0] - coordinates[1][1]),2));
  }
```

```js
distanceBetween([[-23.627,-46.635],[-23.648,-46.588]]); // '32.490177961962594'
```
