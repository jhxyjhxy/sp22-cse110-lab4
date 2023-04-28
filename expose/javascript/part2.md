# Expose Part 2
1. Line 12 will print `3` because the `for` loop uses `var i` and iterates through the `prices` array. Since `var` variables have function scope, `i` should still be `3` even after exiting the `for` loop.
2. Line 13 will print `150` because `var discountedPrice` is updated inside the `for` loop. It is last updated when `i = 2` so `discountedPrice = prices[2] * (1 - 0.5) = 300 * 0.5 = 150`.
3. Line 14 will print `150` because both `var discountedPrice` and `var finalPrice` are last updated when `i = 2`. Since `discountedPrice = 150`, `finalPrice = Math.round(150 * 100) / 100 = 150`.
4. This function will return `discounted` which is the array that stores the `finalPrice` of each of the elements in the input `prices` array. `prices` should be `[50,100,150]`. 
5. The code will cause an error because `i` only has block scope (the `for` loop). 
6. The code will cause an error because `discountedPrice` only has block scope and is defined inside the `for` loop. 
7. Line 14 will print `150` because `finalPrice` is initially defined inside of the function and then updated inside of the `for` loop. 
8. This function will return `discounted` which is the array that stores the `finalPrice` of each of the elements in the input `prices` array. `prices` should be `[50,100,150]`. 
9. This code will cause an error because `i` only has block scope, which is only the `for` loop here.
10. Line 12 will print `3` because `length` is defined to be the size of input array `price`.
11. This function will return `discounted`. `discounted` is a `const` array so its contents can be updated.
12. Notations:
    - `student.name`
    - `student["Grad Year"]`
    - `student.greeting();`
    - `student["Favorite Teacher"].name`
    - `student.courseload[0]`
13. Arithmetic:
    - '32': 2 converts to '2', so '3' concatenates with '2'
    - 1: '3' converts to 3, so 3-2 = 1
    - 3: `null` converts to 0 in numeric conversion, so 3+0 = 3
    - '3null': `null` converts to 'null', so '3' concatenates with 'null' 
    - 4: `true` converts to 1, so 3+1 = 4
    - 0: `false` converts to 0 and `null` converts to 0 as well, so 0+0 = 0
    - '3undefined': `undefined` converts to 'undefined', so '3' concatenates with 'undefined'
    - NaN: '3' converts to 3 while `undefined` converts to `NaN`, so 3-NaN = NaN
14. Comparison:
    - true: '2' is converted to the number 2, so 2 > 1 is true
    - false: '2' and '12' are compared using a "dictionary comparison". Since the first char "2" is greater than the first char in '12' ("1"), '2' should be greater than '12'
    - true: '2' is converted to 2, so 2 is equal to 2
    - false: since 2 is a number and '2' is a string, the `===` operator immediately returns `false` without converting either
    - false: `true` is converted to 1, so 1 should not be equal to 2
    - true: `Boolean(2)` converts to `true`, so `true === true` returns `true`
15. The `==` operator checks equality after type conversion, while the `===` operator checks "strict equality". Both sides of the `===` operator must be of the same type, so if the sides are of different types, the operator returns `false`.
16. In `part2-question16.js`
17. The values in `newArr` will be `[2,4,6]`. The `modifyArray` function takes in the input array `[1,2,3]` and calls the `doSomething` function to double the element at index `i` in the input array `array`. The new value is stored into `newArr`. After each element has been pushed to `newArr`, `newArr` is returned.
18. In `part2-question18.js`
19. 1 <br>
    4 <br>
    3 <br>
    2 <br>