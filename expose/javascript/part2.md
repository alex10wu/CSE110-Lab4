1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^\
Print out 3. Because i is the var variable that keeps track of the for loop. And when i = 3, the for loop should end as i < prices.length == false.
2. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^\
Print out 150. Because the last iteration was assigning the last element of prices * (1 - discount) to discountedPrice, which gives us 300*0.5 = 150.
3. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^\
Print out 150. Because for the last iteration, the value of finalPrice equals to 150 after calling Math.round(150*100)/100.
4. ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^\
Print out array: [50,100,150]. After running the for loop, the array discounted will store all values of each finalPrice in the iteration and based on the input, we know it should be 50, 100, 150 respectively.
5. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^\
Causes an error. The scope of the let variable is within the block. Line 12 refers to i outside of for loop.
6. ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^\
Causes an error. Same reason as question 5, where discountedPrice is a let variable and Line 13 reaches it outside of its scope.
7. ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^\
Print out 150. The let variable finalPrice is assigned with 150 in last iteration and Line 14 is still in the same scope as finalPrice.
8. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why.^^^\
Print out array: [50,100,150]. The discountedPrice and finalPrice are implemented in the same way as appeared in question 4. Since discountedPrice is in the same scope, we should get the same results with no error.
9. ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^\
Causes an error. Line 11 reaches the let variable 'i' outside of its scope.
10. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^\
Print out 3. The length of the array is 3 and 'const length' means it will not change.
11. ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^\
Print out array: [50,100,150]. discountedPrice records finalPrice in each iteration as usual.
12. Given the above Object, write the notation for: (These should be in your part2.md)\
A. console.log(student.name);\
B. console.log(student['Grad Year']);\
C. console.log(student.greeting());\
D. console.log(student['Favorite Teacher'].name);\
E. console.log(student.courseLoad[0]);
13. Arithmetic\
A. '32'. Integers map to their exact string representation. 2 is appended to string '3'.\
B. 1. Subtraction uses number type.\
C. 3. Number type 3 + null which value is 0 results in 3.\
D. '3null'. Here 3 is a string representation and append string 'null' to '3'.\
E. 4. True has value 1 and is converted to a number type. Then 1+3=4\
F. 0. Both false and null have numerical value 0. Thus 0+0=0.\
G. '3undefined'. 'undefined' appends to '3'.\
H. NaN. Undefined will become NaN in Arithmetic Operation.
14. Comparison\
A. True. string '2' becomes a number 2 and 2 is greater than 1.\
B. False. '2' is greater than string '12'.\
C. True. We compare in number type and 2 has same value as '2'.\
D. Error occured. 2 and '2' are different types.\
E. False. We compare in number type and true has value 1 which is not equal to 2.\
F. True. Boolean(2) has value true, which is equal to boolean type true.
15. Explain the difference between the == and === operators.\
== will do type conversion before checking equality. === will compare directly and no type conversion occurs.
16. Given the above Object, write a for...in loop that will iterate through it and print out the value of the property if the property starts with the letter r, or if the value of that property is an odd number.\
See file part2-question16.js
17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result.\
Result will be [2,4,6]. In the for loop, each element in the modifyArray will refer to the function doSomething once and push to the newArr. After finishing the operation, return newArr which multiplied each element by to from the original array.
18. The above program only prints out the time once when executed. Modify this code such that the program prints out the time every second.\
See file part2-question18.js
19. What is the output of the above code?\
1 4 3 2.
