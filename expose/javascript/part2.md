# Part 2

1. The code will output 3 since the for loop will end when i reaches the length of the array which is 3. Line 12 does not error because `var i` has function scope so it is visible anywhere within the function and it is assigned a value before it is used in line 12. 
2. The code will output 150. For the same reasons as question 1 after running the for loop the value of `discountedPrice` will be the last value which was computed for that variable which is 300 * 0.5 = 150.
3. The code will output 150. Since the variable is already an integer value multiplying by 100, rounding, and then dividing by 100 has no effect and the variable remains the same. Once again since the variable is declared with `var` it is usable anywhere within the function it was declared in. 
4. This function returns the resulting array after mutliplying all elements in `prices` by the value `discount` and rounding the value to the nearest cent. In this case the function returns `[50, 100, 150]`.
5. Line 12 will throw an error because the variable `i` is not declared in the same scope as line 12. This is because `i` was declared with `let` which declares the variable in block scope. 
6. Line 13 will also thrown an error for the same reasons as above. `discountedPrice` is not declared in the same scope as line 13.
7. Line 14 will output 150 because the variable `finalPrice` was declared in the same scope as line 14. `finalPrice` will be equal to the last value that is set in the for loop which will be the discounted price to the nearest cent of the last element in `prices`.
8. This function returns the resulting array after mutliplying all elements in `prices` by the value `discount` and rounding the value to the nearest cent. In this case the function returns `[50, 100, 150]`. It doesn't throw an error since `discounted` is in the same scope as line 16.
9. The code will throw an error at line 11 since `i` is not in the same scope as line 11.
10. It will output 3 since that is the value that the constant variable `length` was intialized to. 
11. Since `const` only prevents reassignment, the array is still mutable and can be pushed to. This means it returns `[50, 100, 150]`.

