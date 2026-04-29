# DevTools - Debugging

## Question 1
The bug happened because the values from the input boxes were being read with `.value`, which returns strings. Since JavaScript saw strings, the + operator combined them like text instead of adding them like numbers.

## Question 2
The fix is to convert both inputs into numbers before sending them into calculateSum().

```js
let num1 = Number(document.getElementById("num1").value);
let num2 = Number(document.getElementById("num2").value);