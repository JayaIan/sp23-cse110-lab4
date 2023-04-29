1. 3, prices is an array of length 3 so the loop will execute 3 times when the loop finishes i maintians its value of 3.
2. 150, in the last iteration of the loop the price of 300 is discounted by 0.5 giving the value of 150 stored in the variable discountedPrice
3. 150, in the last iteration of the loop the price of 300 is discounted by 0.5 giving the value of 150 stored in the variable discountedPrice. This value is then multiplied by 100, rounded and divided by 100, since there is no rounding necessary the finalPrice value is also 150.
4. It will return the array [ 50, 100, 150 ] which is each of the finalPrice values for the intial prices inputted into the discountPrices function.
5. Line 12 produces an error because it tries accessing the variable i which has gone out of scope since it was defined using let in the for loop block. 
6. Line 13 produces an error because it tries accessing the variable i which has gone out of scope since it was defined using let in the for loop block. 
7. Line 14 prints 150, in the last iteration of the loop the price of 300 is discounted by 0.5 giving the value of 150 stored in the variable discountedPrice, since discountedPrice was defined using let within the scope of the function it is still defined
8. It will return the array [ 50, 100, 150 ] which is each of the finalPrice values for the intial prices inputted into the discountPrices function. Since finalPrice is defined using let within the function block, the return statement is within that scope and thus able to access it. 
9. Line 11 produces an error because it tries accessing the variable i which has gone out of scope since it was defined using let in the for loop block. 
10. Line 12 will print 3, because length is in scope and defined to be 3, which does not change during the execution of the function.
11. It will return the array [ 50, 100, 150 ] which is each of the finalPrice values for the intial prices inputted into the discountPrices function. Although the array reference is a const, the values in the array are not constant so values can be added to the array. 
12. Questions about student object
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[1]
13. Arithmetic
    1.  '32': Plus is interpreted as a string operation so 2 is converted to a string and concatinated to the string '3' to get the string '32'.
    2.  1: Minus is interpreted as a math operation so '3' is converted into the value 3 and 2 is subtracted to get the value 1.
    3.  3: Plus is interpreted as a math operation so null is converted into the value 0 and 3 is added to get the value 3.
    4.  '3null': Plus is interpreted as a string operation so null is converted to a string and concatinated to the string '3' to get the string '3null'.
    5.  4: Plus is interpreted as a math operation so true is converted into the value 1 and 3 is added to get the value 4.
    6.  0: Plus is interpreted as a math operation so false is converted into the value 0 and null is converted into the value 0 both are added to get the value 0.
    7.  '3undefined': Plus is interpreted as a string operation so undefined is converted to a string and concatinated to the string '3' to get the string '3undefined'.
    8.  NaN: Minus is interpreted as a math operation so '3' is converted into the value 3 and undefined is converted into the value NaN, these are subtracted to get the value NaN.
14. Comparison
    1.  true: the string '2' is converted into the number value 2 which is greater than 1, so true is returned
    2.  false: the two strings are compared in lexicographical order since the first character '2' is greater than '1', so false is returned.
    3.  true: the string '2' is converted into the number value 2 which is equal to 2, so true is returned
    4.  false: since the two types being compared are not the same type the strict equality operator returns false. 
    5.  false: true is converted into the number value 1 which is not equal to 2, so false is returned
    6.  true: Boolean(2) returns the Boolean value true, since this is compare to the value true which is the same type the strict equality operator returns true. 
15. The == operator compares only the values of the two operands. Meanwhile the === operator compare both the type and the values of the two operands. 
16. See part2-question16.js
17. This will return an array with the values [2, 4, 6], this is because the function modifyArray will use the callback function doSomething which is called on each value of the input array to double it and push it into newArr
18. See part2-question18.js
19. Ouput: 
1
4
3
2