# Expose Part 1
1. values added: 20
2. final result: 20
3. values added: 20
4. This code returns an error since `let` has block scope. So `result` is only visible inside the `if` block.
5. This code returns an error since the `const` keyword prevents `result` from being reassigned. Since we attempt to reassign `result` on line 7, an error is thrown.
6. This code returns an error for the same reason as (5.). In addition, `const` variables have block scope like `let` variables.