# JavaScript Array methods

It's as simple, as it looks, given the array of objects, count how many people have voted, return the count.

```javascript
const voters = [
  { name: "Bob", age: 30, voted: true },
  { name: "Jake", age: 32, voted: true },
  { name: "Kate", age: 25, voted: false },
  { name: "Sam", age: 20, voted: false },
  { name: "Phil", age: 21, voted: true },
  { name: "Ed", age: 55, voted: true },
  { name: "Tami", age: 54, voted: true },
  { name: "Mary", age: 31, voted: false },
  { name: "Becky", age: 43, voted: false },
  { name: "Joey", age: 41, voted: true },
  { name: "Jeff", age: 30, voted: true },
  { name: "Zack", age: 19, voted: false },
];
// 7 voters
```

Now, back to the first array of objects. Let's practice the **reduce** method.
Build the following object out of the initial one.

```javascript
const result = {
  Becky: 43,
  Bob: 30,
  Ed: 55,
  Jake: 32,
  Jeff: 30,
  Joey: 41,
  Kate: 25,
  Mary: 31,
  Phil: 21,
  Sam: 20,
  Tami: 54,
  Zack: 19,
};
```

The same array, now let us practice the _sort_ method, sort the voters by age, from youngest to oldest.

```javascript
const voters = [
  { name: "Bob", age: 30, voted: true },
  { name: "Jake", age: 32, voted: true },
  { name: "Kate", age: 25, voted: false },
  { name: "Sam", age: 20, voted: false },
  { name: "Phil", age: 21, voted: true },
  { name: "Ed", age: 55, voted: true },
  { name: "Tami", age: 54, voted: true },
  { name: "Mary", age: 31, voted: false },
  { name: "Becky", age: 43, voted: false },
  { name: "Joey", age: 41, voted: true },
  { name: "Jeff", age: 30, voted: true },
  { name: "Zack", age: 19, voted: false },
];
// just do your magic
```

Here is a wishlist, count the total price for all items in the wishlist.

```javascript
const wishlist = [
  { title: "Tesla Model S", price: 90000 },
  { title: "4 carat diamond ring", price: 45000 },
  { title: "Fancy hacky Sack", price: 5 },
  { title: "Gold fidgit spinner", price: 2000 },
  { title: "A second Tesla Model S", price: 90000 },
];
// 227005
```
