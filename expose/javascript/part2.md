1. The final value of i, 3 is printed. This is valid because although i is declared within the for loop, it has type var, which is function-scoped. Therefore, it can be accessed anywhere in discountPrices.
2. The final value of discountedPrice, 150 is printed. This is because discountedPrice was declared as var within the same function as the console.log statement.
3. The final value of finalPrice, 150 is printed. finalPrice was declared as a var within the same function.
4. It returns the array [50, 100, 150], since for each iteration in the for loop, the value of finalPrice is pushed to the discounted array.
5. There is an error, because i is declared as a let in the header of the for loop, so it is block-scoped and cannot be accessed outside of the for loop.
6. There is an error, because discountedPrice is declared as a let in the for loop, so it is block-scoped and cannot be accessed outside of the for loop.
7. The final value of finalPrice, 150 is printed. finalPrice was declared as a let within the same block, so it can be reassigned.
8. It returns the array [50, 100, 150], since for each iteration in the for loop, the value of finalPrice is pushed to the discounted array.
9. There is an error, because i is declared as a let in the header of the for loop, so it is block-scoped and cannot be accessed outside of the for loop.
10. The value of length, 3 is printed. This is because length was declared as a const within the same block as the console.log statement.
11. It returns the array [50, 100, 150], since for each iteration in the for loop, the value of discountedPrice is pushed to the discounted array.
12.
    A. student.name
    B. stduent["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. 
    A. '32' since integers are mapped to their exact string value.
    B. 1, it doesn't make sense to subtract a number from a string, so the string is converted to its number representation.
    C. 3, null is converted to 0.
    D. 3null, null is converted to its string representation, which is "null"
    E. 4, true is converted to 1.
    F. 0, false is converted to 0, and null is converted to 0.
    G. 3undefined, undefined is converted to its string representation, which is "undefined"
    H. NaN, the string is converted to its number representation, which is 3, and undefined is converted to its number representation, which is NaN. Any operation with NaN is NaN.
14.
    A. true, the string '2' is converted to its number representation, which is 2. 2 > 1 is true.
    B. false, the string '2' is lexically greater than the string '12'.
    C. true, the string '2' is converted to its number representation, which is 2. 2 == 2 is true.
    D. false, the string '2' is not converted to a number because of the strict equality, so it is not equal to 2.
    E. false, true is converted to 1, and 1 != 2 is false.
    F. true, Boolean(2) is true because 2 is not 0, undefined, the empty string, null, or NaN. true === true is true.
15.  The == operator is a non-strict equality operator, which means that it will attempt to convert the operands to the same type before comparing them. The === operator is a strict equality operator, which means that it will not attempt to convert the operands to the same type before comparing them.
16. see part2-question16.js
17. The result is the array [2, 4, 6]. The function modifyArray iterates through the array and for each element, it uses the callback function (which multiplies the element by 2 in this case) and pushes the result to the newArr array. Therefore, the result is the input array where each element has been multiplied by 2.
18. see part2-question18.js
19. The output is:
    1
    4
    3
    2
