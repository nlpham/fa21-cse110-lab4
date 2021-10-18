# Part 2 Answers
## Question 1
Line 12 will return prices.length because that is the last value before exiting the for loop and since i is defined using var, it can be reached outside of the block scope.
## Question 2
Line 13 will return the last discountedPrice, 150, since that was the last updated value of discountedPrice and it was defined using var.
## Question 3
Line 14 will give us the last updated finalPrice from the loop, 150, since var is a function level variable.
## Question 4
This function will return an array of discounted prices [50,100,150]. This is because every variable was defined using var and can be accessed globally. Thus discounted price and final price would be updated for each iteration of the loop and pushed into a new array of discounted prices to be returned.
## Question 5
Line 12 will give an error since i is defined inside of the for code block but is being referenced outside of the for block.
## Question 6
This will give an error since discountedPrice was defined using let inside of the for loop code block.
## Question 7
Line 14 will give us the last updated final price from the for loop,150. Since finalPrice was defined in the function block, it can be accessed.
## Question 8
This function will return [50,100,150]. Though the variables are defined as let, they are all referenced within their respective code blocks thus allowing us to build and return the discounted array.
## Question 9
The code causes an error because line 7 is trying to update a constant variable.
## Question 10
This code still results in an error since we are still trying to update the value of a constant variable.
## Question 11
This code results in an error since the for loop tries to update a constant value.
## Question 12
### A
student.name;
### B
student['Grad Year'];
### C
student.greeting();
### D
student['Favorite Teacher'].name;
### E
student.courseLoad[0];
## Question 13
### A
'3' + 2 = '32'
because integers map to their string representation
### B
'3' - 2 = 1
because operands are converted to numbers.
### C
3 + null = 3
because null is the abscence of value.
### D
'3' + null = 3null
because string addition concatenates.
### E
true + 3 = 4
because true maps to 1 
### F
false + null = 0
because false maps to 0
### G
'3' + undefined = 3undefined
string addition concatenates.
### H
'3' - undefined = NaN
undefined operation returns NaN
## Question 14
### A
True, '2' is converted to integer value 2.
### B
False, the first character from '2' is greater than the first character from '12' , so '2' is greater.
### C
True, '2' is converted to integer value 2.
### D
False, this is a strict equality and the types are different.
### E
False, true maps to 1.
### F
True, Boolean(2) is true. Anything without a value is false.
## Question 15
=== is a strict equality and will check the equality without type conversion. ==, however, does do type conversion and can equate two different types.
## Question 17
This returns [2,4,6], modify array takes each element of the array given as parameter and uses the callback function to multiply the value by two, then it is pushed into a new array to be returned.
## Question 19
The output would be in the following order 1 4 3 2.