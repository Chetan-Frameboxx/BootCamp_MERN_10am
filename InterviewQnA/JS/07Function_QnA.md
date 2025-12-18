# JavaScript Functions – Interview Questions & Answers
---

## 1. What is a function in JavaScript?

**Answer:**
A function is a reusable block of code that performs a specific task. Instead of writing the same logic again and again, we can place it inside a function and call it whenever required. Functions help make code clean, organized, and easy to maintain.

---

## 2. What is a normal function?

**Answer:**
A normal function is defined using the `function` keyword. It can have a name, accept parameters, return values, and can be reused multiple times in a program. Normal functions also have their own scope and execution context.

---

## 3. How do you call a normal function?

**Answer:**
A normal function is called by writing the function name followed by parentheses `()`. If the function expects parameters, values are passed inside the parentheses.

---

## 4. What is function hoisting?

**Answer:**
Function hoisting means that normal function declarations are moved to the top of their scope by JavaScript during execution. Because of this, a normal function can be called before it is defined in the code.

---

## 5. What is an arrow function?

**Answer:**
An arrow function is a modern and shorter way to write functions using the `=>` syntax. It reduces the amount of code needed and is commonly used for simple logic and small operations.

---

## 6. Why are arrow functions used?

**Answer:**
Arrow functions are used to make the code shorter, cleaner, and more readable. They are especially useful when writing simple functions or working inside loops and conditions.

---

## 7. Do arrow functions have their own `this`?

**Answer:**
No, arrow functions do not have their own `this`. Instead, they use `this` from the surrounding scope. This helps avoid confusion when working inside nested functions.

---

## 8. Difference between normal function and arrow function?

**Answer:**
Normal functions have their own `this` keyword and are hoisted. Arrow functions do not have their own `this` and are not hoisted in the same way because they are usually stored in variables.

---

## 9. What is an anonymous function?

**Answer:**
An anonymous function is a function that does not have a name. It is usually assigned to a variable or used where a function is needed only once.

---

## 10. Why are anonymous functions used?

**Answer:**
Anonymous functions are used when we do not need to reuse the function multiple times. They are commonly used to keep the code simple and avoid unnecessary function names.

---

## 11. Can an anonymous function be reused?

**Answer:**
Yes, if an anonymous function is assigned to a variable, it can be reused by calling that variable like a function.

---

## 12. What is an IIFE?

**Answer:**
An IIFE (Immediately Invoked Function Expression) is a function that runs immediately after it is defined. It does not require a separate function call.

---

## 13. Why is IIFE used?

**Answer:**
IIFE is mainly used to execute code immediately and to avoid creating variables in the global scope. This helps prevent name conflicts in larger programs.

---

## 14. Does an IIFE need to be called manually?

**Answer:**
No, an IIFE runs automatically as soon as it is defined because it is immediately invoked.

---

## 15. Can an IIFE take parameters?

**Answer:**
Yes, values can be passed to an IIFE just like a normal function. This allows dynamic data to be used inside the IIFE.

---

## 16. Are arrow functions anonymous by default?

**Answer:**
Yes, arrow functions are anonymous by default. When they are assigned to a variable, the variable name is used to call the function.

---

## 17. What happens if a function does not return anything?

**Answer:**
If a function does not use the `return` keyword, JavaScript automatically returns `undefined`.

---

## 18. Can a function return a value?

**Answer:**
Yes, a function can return a value using the `return` statement. This returned value can be stored in a variable or used in expressions.

---

## 19. Can functions be stored in variables?

**Answer:**
Yes, in JavaScript functions are treated like values. They can be stored in variables, passed around, and executed using the variable name.

---

## 20. Why are functions important in JavaScript?

**Answer:**
Functions help reduce repetition, improve readability, make debugging easier, and allow large programs to be divided into smaller, manageable parts.

---

