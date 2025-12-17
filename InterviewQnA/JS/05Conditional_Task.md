# JavaScript Interview Q&A – Objects and Arrays


**Q1: What is an object in JavaScript?**

* Collection of key-value pairs where keys are strings or symbols and values can be any data type.

**Q2: How to create an object?**

```js
const obj = {name: 'John', age: 30};
const obj2 = new Object();
```

**Q3: How to access object properties?**

```js
obj.name; // dot notation
obj['age']; // bracket notation
```

**Q4: How to add or update properties in an object?**

```js
obj.gender = 'male';
obj['city'] = 'Delhi';
```

**Q5: How to delete a property from an object?**

```js
delete obj.age;
```

**Q6: How to check if a property exists in an object?**

```js
'age' in obj; // true/false
obj.hasOwnProperty('name'); // true/false
```

**Q7: How to iterate over object properties?**

```js
for(let key in obj) {
  console.log(key, obj[key]);
}
```

**Q8: What is an array in JavaScript?**

* An ordered collection of elements, indexed from 0.

**Q9: How to create an array?**

```js
const arr = [1,2,3];
const arr2 = new Array(1,2,3);
```

**Q10: How to access array elements?**

```js
arr[0]; // 1
```

**Q11: How to add elements to an array?**

```js
arr.push(4); // end
arr.unshift(0); // start
```

**Q12: How to remove elements from an array?**

```js
arr.pop(); // end
arr.shift(); // start
```

**Q13: How to find the length of an array?**

```js
arr.length;
```

**Q14: How to iterate over an array?**

```js
arr.forEach(item => console.log(item));
```

**Q15: What are some common array methods?**

* `map()`, `filter()`, `reduce()`, `slice()`, `splice()`, `includes()`, `indexOf()`

**Q16: How to merge two arrays?**

```js
const arr3 = arr.concat(arr2);
// or using spread
const arr4 = [...arr, ...arr2];
```

**Q17: How to clone an array?**

```js
const newArr = [...arr];
const newArr2 = arr.slice();
```

**Q18: How to convert an array to a string?**

```js
arr.join(',');
arr.toString();
```

**Q19: How to convert a string to an array?**

```js
const str = '1,2,3';
const arr = str.split(',');
```

**Q20: What is the difference between an array and an object?**

* Arrays are ordered lists with numeric indices; objects are key-value collections without guaranteed order.
