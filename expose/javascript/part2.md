1. The value of i is printed which would be 3
2. The value of discountedPrice that was given when prices[2] will be printed which is 150
3. The value of finalPrice that was given when discountedPrice was 150 will be printed which is 150
4. This function will return an array with the final prices after the discount as values
5. This will cause an error since variables made by let such as i is only visible in its block which is the for loop, so it will be undefined when it gets to line 12
6. This will cause an error since variables made by let such as discountedPrice is only visible in its block which is the for loop, so it will be undefined when it gets to line 13
7. The value of finalPrice will be printed, which would be 150.
8. This function will return an array with the final prices after the discount as values
9. This will cause an error since variables made by let such as i is only visible in its block which is the for loop, so it will be undefined when it gets to line 11
10. This will print the value of length which is 3.
11. This will return an array of the discounted prices
12. 
    a) student.name
    b) student["Grad Year"]
    c) student.greeting()
    d) student["Favorite Teacher"].name
    e) student.courseLoad[0]
13. 
    a) '32', since 2 will become a string and the '3' + '2' will concentenate to make '32'
    b) 1, since there is no "-" in string operations, the '3' is converted into a number resulting in 3-2 which is 1
    c) 3, since null will be treated like a number and become 0 and 3+0 = 3
    d) '3null', since null will be treated like a string and be concentenated to 3
    e) 4, since true will become 1 and be added to 3 and 3+1 = 4
    f) 0, since both of them wil become numbers and false is 0 and null is also 0 when converted to number and 0+0 = 0
    g) '3undefined', since undefined will become a string and be cocentenated to 3
    h) NaN, since "-" is a strictly numerial operation, both '3' and undefined try to become numbers, which will make both of them NaN, so the result is NaN
14. 
    a) true, since '2' will become a number and 2 is greater than 1
    b) false, since they are both strings and since '1' is less than '2' in the first comparison, making the statement false
    c) true, since '2' will become a number and 2 = 2
    d) false, since they are different types
    e) false, since true will become 1 and 1 does not equal 2
    f) true, since Boolean(2) will return true, which makes the statement true === true, which is true
15. The == operator will try to convert the operands into the same type to see if they will be equal when they are the same type, while the === operator will check for complete equality, which means it will not try to convert either operand and sees each variable as its original type, which makes it return true only when they are equal in type and values.
16. (in part2-question16.js)
17. The result will be [2, 4, 6]. We will go through the for loop and for each iteration we will use the function doSomething on array[i], which will double its value. We will then push that value into the newArr. After the for loop ends, we will return the newArr which is our answer.
18. in part2-question18.js
19. 1432