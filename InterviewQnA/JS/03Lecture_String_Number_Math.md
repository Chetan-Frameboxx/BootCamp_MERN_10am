# JavaScript Interview Q&A – Data Types and Methods


**Q1: What are the different data types in JavaScript?**

* **Primitive:** string, number, boolean, null, undefined, symbol, bigint
* **Non-primitive (Objects):** object, array, function

**Q2: What is the difference between `null` and `undefined`?**

* `undefined` means a variable is declared but not assigned.
* `null` is an assigned value representing "no value".

**Q3: What is `NaN`?**

* Stands for Not-a-Number, represents invalid number operations.

**Q4: How to check the type of a variable?**

```js
typeof 42; // 'number'
typeof 'hello'; // 'string'
```

**Q5: How to convert a string to a number?**

```js
Number('123'); // 123
parseInt('123'); // 123
parseFloat('123.45'); // 123.45
```

**Q6: How to convert a number to a string?**

```js
String(123); // '123'
123..toString(); // '123'
```

**Q7: What is the difference between `==` and `===`?**

* `==` compares values with type coercion.
* `===` compares value and type strictly.

**Q8: How to check if a variable is an array?**

```js
Array.isArray([1,2,3]); // true
```

**Q9: What is the difference between `let` and `const` data type assignment?**

* `let` allows reassignment, `const` prevents reassignment.

**Q10: What are string methods in JavaScript?**

* `length`, `toUpperCase()`, `toLowerCase()`, `trim()`, `split()`, `includes()`, `replace()`

**Q11: What are number methods in JavaScript?**

* `toFixed()`, `toString()`, `parseInt()`, `parseFloat()`, `isNaN()`, `Number()`

**Q12: What are array methods in JavaScript?**

* `push()`, `pop()`, `shift()`, `unshift()`, `slice()`, `splice()`, `map()`, `filter()`, `reduce()`, `forEach()`

**Q13: What are object methods in JavaScript?**

* `Object.keys()`, `Object.values()`, `Object.entries()`, `hasOwnProperty()`, `assign()`

**Q14: What is a symbol data type?**

* Unique and immutable primitive value, often used as object property keys.

**Q15: What is a BigInt?**

* Represents integers larger than `Number.MAX_SAFE_INTEGER`.
* Example: `123n`.

**Q16: How to check if a value is `null` or `undefined`?**

```js
value === null // checks null
value === undefined // checks undefined
```

**Q17: What is type coercion in JavaScript?**

* Automatic conversion of one data type to another during operations.
* Example: `'5' + 2` results in `'52'`

**Q18: How to clone an object?**

```js
const obj2 = {...obj1}; // shallow copy
```

**Q19: How to get the length of an array or string?**

```js
arr.length
str.length
```

**Q20: How to convert a string to boolean?**

```js
Boolean('true'); // true
Boolean(''); // false
```
