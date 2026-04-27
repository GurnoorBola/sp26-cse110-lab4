# Part 1

1. It prints `value added: 20` since 10 + 10 is 20.
2. It prints `final result: 20` since the `var` declaration has function scope.
3. You should not use var because it can cause naming collisions with variables or functions declared outside of the block that it was declared in. This can cause silent errors that can be hard to debug and it fills the namespace with unecessary clutter making it harder to program. 
4. It prints `value added: 20` since 10 + 10 is 20.
5. Line 13 throws an error because when declaring a variable with `let` the variable has block scope meaning that it can only be used within the block that it was declared in including nested blocks. Since `result` is not in the scope of the variable `result` it will result in an error. 
6. Line 7 throws an error because a `const` variable cannot be reassigned. 
7. Firstly, the program won't reach line 13 since it will error at line 7 but even if it did not error at line 7 we would get another error due to `result` not being in the same scope as the code at line 13.
