# JavaScript Interview Q&A – Lecture 02: Variables


**Q1: What is the difference between `var`, `let`, and `const`?**

* `var` is function-scoped, can be re-declared and updated.
* `let` is block-scoped, can be updated but not re-declared.
* `const` is block-scoped, cannot be updated or re-declared.

**Q2: Can you reassign a `const` object or array?**

* You cannot reassign it, but you can modify its properties or elements.

**Q3: What is the temporal dead zone (TDZ)?**

* TDZ is the time between entering a scope and the declaration of a `let` or `const`. Accessing during this period causes a `ReferenceError`.

**Q4: What is hoisting?**

* Variable and function declarations are moved to the top of their scope. `var` is initialized as `undefined`, `let` and `const` are uninitialized.

**Q5: What will be the output?

````js
console.log(a);
var a = 5;
console.log(b);
let b = 10;
```**
- Output: `undefined` then `ReferenceError`.
````

**Q6: Can `var` be re-declared inside the same function?**
- Yes, `var` can be re-declared in the same scope.

**Q7: Can `let` be re-declared inside the same block?**
- No, re-declaration of `let` in the same block is not allowed.

**Q8: Can `const` variables be declared without initialization?**
- No, `const` must be initialized at the time of declaration.

**Q9: Difference between global variables declared with `var` vs `let`?**
- `var` attaches to `window` object (in browsers); `let` does not.

**Q10: Are `var` variables hoisted?**
- Yes, they are hoisted and initialized with `undefined`.

**Q11: Are `let` and `const` hoisted?**
- Yes, but they are not initialized and accessing them before declaration causes a `ReferenceError`.

**Q12: What is the scope of `var`?**
- Function-scoped.

**Q13: What is the scope of `let` and `const`?**
- Block-scoped.

**Q14: Can you use a `let` variable before declaring it?**
- No, it will throw a `ReferenceError` due to TDZ.

**Q15: Can you use a `const` variable before declaring it?**
- No, same as `let`, it is in TDZ.

**Q16: Can you update a `let` variable?**
- Yes, `let` can be updated.

**Q17: Can you update a `const` variable?**
- No, the variable reference cannot be updated.

**Q18: What happens if you declare `var` inside a block?**
- It is function-scoped, so accessible outside the block within the function.

**Q19: What happens if you declare `let` inside a block?**
- It is block-scoped, so not accessible outside the block.

**Q20: Why use `let` or `const` over `var`?**
- They provide block-scoping, prevent accidental re-declaration, and reduce bugs caused by hoisting.
````
