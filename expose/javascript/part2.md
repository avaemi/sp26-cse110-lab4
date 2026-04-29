# Question 1
Line 12 prints `3` because `i` was declared with `var`, so it is still available after the loop ends. After the loop finishes, `i` has reached 3.

# Question 2
Line 13 prints `150` because `discountedPrice` was declared with `var`, so it can still be accessed after the loop. The last price was 300, and 50% off makes it 150.

# Question 3
Line 14 prints `150` because `finalPrice` was declared in the function using `var`. After the final loop, it stores the last discounted price.

# Question 4
The function returns `[50, 100, 150]` because each price is discounted by 50% and then added into the array.

# Question 5
Line 12 gives a ReferenceError because `i` was declared with `let` inside the loop, so it only exists inside that loop.

# Question 6
Line 13 gives a ReferenceError because `discountedPrice` was declared with `let` inside the loop, so it cannot be accessed after the loop ends.

# Question 7
Line 14 prints `150` because `finalPrice` was declared outside the loop, so it is still available inside the function.

# Question 8
The function returns `[50, 100, 150]` because the discounted values are pushed into the array and returned at the end.

# Question 9
Line 11 gives a ReferenceError because `i` was declared with `let` inside the loop and is not available outside of it.

# Question 10
Line 12 prints `3` because `length` is declared with `const` and stores `prices.length`, which is 3.

# Question 11
The function returns `[50, 100, 150]`. The array itself is declared with `const`, but values can still be pushed into it.

# Question 12
A. `student.name`  
B. `student["Grad Year"]`  
C. `student.greeting()`  
D. `student["Favorite Teacher"].name`  
E. `student.courseLoad[0]`

# Question 13
A. `'32'` because `+` with a string causes concatenation.  
B. `1` because `-` converts the string to a number.  
C. `3` because `null` becomes 0 in numeric addition.  
D. `'3null'` because the string causes concatenation.  
E. `4` because `true` becomes 1.  
F. `0` because `false` and `null` both become 0.  
G. `'3undefined'` because the string causes concatenation.  
H. `NaN` because `undefined` becomes NaN in subtraction.

# Question 14
A. `true` because `'2'` is converted to the number 2.  
B. `false` because both values are strings, so JavaScript compares them alphabetically.  
C. `true` because `==` allows type conversion.  
D. `false` because `===` checks both value and type.  
E. `false` because `true` becomes 1, and 1 is not equal to 2.  
F. `true` because `Boolean(2)` is true, and both sides are true.

# Question 15
`==` compares values after converting types when needed. `===` compares both the value and the type without converting. For example, `2 == "2"` is true, but `2 === "2"` is false.

# Question 17
The result is `[2, 4, 6]`. The function goes through `[1, 2, 3]`, calls `doSomething` on each number, doubles it, and stores the result in a new array.

# Question 19
The output is `1, 4, 3, 2`.

The first number prints right away. The timeout for 2 waits longer, while the timeout for 3 has a delay of 0. The number 4 still prints before 3 because normal synchronous code finishes before the timeout callback runs.