**Q1:** 3 gets printed, which is the value of i after exiting the for loop

**Q2:** 150 gets printed as it is the value of the updated discountedPrice when the calculation ends and exits the loop

**Q3:** 150 is printed and like discountedPrice, it is the last value calculated and stored after exiting the loop

**Q4:** The function returns the array discounted, which holds the discounted prices: [50,100, 150]

**Q5:** An error will occur because the scope of i will only be valid within the for-loop, once it exists the loop i is no longer defined therefore cannot be printed.

**Q6:** An error will be raised similar to question 5, here discountedPrice has a scope only valid inside the loop, and is no longer defined after exiting the loop

**Q7:** 150, as the scope of finalPrice is still valid after exiting the loo as it was defined before. The scope of the variable is the function itself, so it will still be defined when printed on line 14.

**Q8:** Code returns the array discounted which has a value of: [5,100,150], which are the prices passed in after applying the discount.

**Q9:** An error will occur because the scope of i will only be valid within the for-loop, once it exists the loop i is no longer defined therefore cannot be printed.

**Q10:** 3 will be printed as that the number of elements defined as a constant initially by the length of the prices array.

**Q11:** [ 50, 100, 150 ] the value of the discounted array, there is no error when changing the value of the const discountedPrice as every time the loop begins the variable gets re-initialized and is able to change.

**Q12:** 
    A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];

**Q13:**
```js
A > '3'+2
'32'

B > '3'-2
1

C > 3 + null
3

D > '3' + null
'3null'

E > true + 3
4

F > false + null
0

G > '3' + undefined
'3undefined'

H > '3' - undefined
NaN
```
**Q14:**
```js
A > '2'>1
true

B > '2'<'12'
false

C > 2 == '2'
true

D > 2 === '2'
false

E > true == 2
false

F > true === Boolean(2)
true
```

**Q15:** The == does the type conversion between operands before the comparison, while === compares the values and the data types of each operand. 

**Q17:** The result from the call will be [2, 4, 6]. What is occurring is an array and function gets passed into the modifyArray function. Inside there's a loop will grab every element from the parameter array and pass it through the parameter function, which modifies the element and returns the element but multiplied by 2. Afterwards this number is then pushed onto the new array initiated in the first function and the process gets repeated.

**Q19:** 1432