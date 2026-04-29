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
12. 
    A. `student.name`
    B. `student['Grad Year']`
    C. `student.greeting()`
    D. `student['Favorite Teacher'].name`
    E. `student.courseLoad[0]`
13.
    A. It outputs `'32'` since it converts 2 to a string and concatenates it to the string 3. 
    B. It outputs `1` since it converts the string 3 to a integer and performs subtraction by 1.
    C. It outputs `3` since null is converted to the integer value 0 and 3 + 0 = 3.
    D. It outputs `'3null'` since null is converted to the string `'null'` and is concatenated to the string 3.
    E. It outputs `4` since true is converted to the integer value 1 and 1 + 3 = 4.
    F. It outputs `0` since false is converted to the integer 0 and null is converted to the integer 0 and 0 + 0 = 0.
    G. It outputs '3undefined' since undefined is converted to a string and concatenated to the string 3.
    H. It outputs NaN since the string 3 is converted to a number and undefined is converted to NaN. Anything subtracted by NaN is NaN.
14. 
    A. It outputs `true` because '2' gets converted into the integer 2 and 2 > 1.
    B. It outputs `false` since the strings are compared in lexiographical order and since the character '2' > '1' the inequality returns false. 
    C. It outputs `true` because the string 2 gets converted to a ineteger and 2 is equal to 2.
    D. It outputs `false` since the two operands of the operator are not of the same type so they cannot be equivalent. 
    E. It outputs `false` since true is converted to the integer value 1 and 1 does not equal 2.
    F. It outputs `true` since Boolean(2) resolves to the boolean value `true` since any non zero integer value will be truthy. Since true is equal to true the operator returns true.

15. Using the `==` operator will cause type conversions but using `===` will not convert types and will return false if the operands are of a different type form each other. 

17. modifyArray(\[1,2,3\], doSomething) returns a new array with the values \[2, 4, 6\]. The function iterates throught the array that is passed in as an argument to modifyArray. Then for every element in the array it applies the callback function which is doSomething. doSomething returns 2 times the value that was passed to it. Finally this value is pushed to a new array.

19. It outputs 1 3 4 2.

