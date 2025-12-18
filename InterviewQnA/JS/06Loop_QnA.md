# JavaScript Interview Q&A – Loops


**Q1: What types of loops are there in JavaScript?**

* `for`, `while`, `do...while`, `for...in`, `for...of`

**Q2: Syntax of a `for` loop?**

```js
for(let i = 0; i < 5; i++) {
  console.log(i);
}
```

**Q3: Syntax of a `while` loop?**

```js
let i = 0;
while(i < 5) {
  console.log(i);
  i++;
}
```

**Q4: Syntax of a `do...while` loop?**

```js
let i = 0;
do {
  console.log(i);
  i++;
} while(i < 5);
```

**Q5: Difference between `while` and `do...while`?**

* `while` checks condition before executing block.
* `do...while` executes block at least once before checking condition.

**Q6: What is `for...in` loop used for?**

* Iterates over **enumerable properties** of an object.

```js
for(let key in obj) { console.log(key, obj[key]); }
```

**Q7: What is `for...of` loop used for?**

* Iterates over **iterable objects** like arrays, strings, sets.

```js
for(let val of arr) { console.log(val); }
```

**Q8: Can loops be nested?**

* Yes, any loop can be nested inside another loop.

**Q9: How to exit a loop prematurely?**

* Using `break` statement.

**Q10: How to skip an iteration in a loop?**

* Using `continue` statement.

**Q11: Difference between `for...in` and `for...of`?**

* `for...in` iterates over keys/properties.
* `for...of` iterates over values.

**Q12: Can `for...of` loop iterate objects?**

* No, objects are not iterable; use `Object.keys()` or `Object.entries()`.

**Q13: How to loop through an array using `forEach()`?**

```js
arr.forEach((item, index) => console.log(item, index));
```

**Q14: What is an infinite loop?**

* A loop that never ends, usually due to wrong condition.

**Q15: How to avoid infinite loops?**

* Ensure loop condition will eventually become false.

**Q16: Can `let` or `const` be used in loop counters?**

* `let` is commonly used; `const` cannot be incremented.

**Q17: How to break out of nested loops?**

* Use **labels** with `break`.

```js
outer: for(let i=0;i<5;i++) {
  for(let j=0;j<5;j++) {
    if(j===3) break outer;
  }
}
```

**Q18: Difference between `map()` and `forEach()`?**

* `map()` returns a new array; `forEach()` returns undefined.

**Q19: Difference between `for` and `while` loops?**

* `for` has initialization, condition, increment in one line; `while` separates them.

**Q20: Can loops be asynchronous?**

* Loops themselves are synchronous, but `async/await` or `Promises` can be used inside loops for async operations.
