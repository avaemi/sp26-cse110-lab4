# Question 1
Line 9 prints `values added: 20`.

# Question 2
Line 13 prints `final result: 20`.

# Question 3
You should avoid using `var` because it is function-scoped, not block-scoped. This can make variables available in places you did not expect, which makes bugs harder to catch.

# Question 4
Line 9 prints `values added: 20`.

# Question 5
Line 13 gives a ReferenceError because `result` was declared with `let` inside the if block, so it cannot be used outside of that block.

# Question 6
Line 9 gives a TypeError because `result` was declared with `const`, and the code tries to reassign it after that.

# Question 7
Line 13 does not run because the TypeError already stops the program. Also, `const` is block-scoped, so `result` would not be available outside the if block anyway.