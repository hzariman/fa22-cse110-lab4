# Part 2. A Little More of a Challenge
1. 3 would be outputted because the iteration variable i is the reaches 3 (since it is incremented in the for loop and there were 3 iterations)
   
2. 150 would be outputted because the last element to be assigned to the vairable discounted price is in the third iteration where prices[i] = 300. Then, by line 7, discounted price is calculated to be 300 * (1- 0.5) = 150.
   
3. 150 would be outputted because finalPrice was declared as a var in the scope of the function so it retains the last value assigned.

4. An array of values [ 50, 100, 150 ] will be returned. This is because the final price after each iteration of elements in prices is pushed to a VAR array declared at the started of the function (as seen in line 9) which has a scope of the whole function. 
   
5. Error because i is defined as 'let' and so it only exists in the scope of the for loop and not the whole function. Thus, it can't be accessed in the scope of line 12.

6. Error because discountedPrice is defined as 'let' and so it only exists in the scope of the for loop and not the whole function. Thus, it can't be accessed in the scope of line 13.

7. 150 would be outputted finalPrice was declared as a let in the scope of the function (and so exists throughout this scope). Furthermore, it retained the last value it was assigned which was calculated as 150. 

8. An array of values [ 50, 100, 150 ] will be returned. This is because the final price after each iteration of elements in prices is pushed to a let array declared at the started of the function (as seen in line 9) which has a scope of the whole function and so can be accessed throughout. 

9. Error because i is defined as 'let' and so it only exists in the scope of the for loop and not the whole function. Thus, it can't be accessed in the scope of line 11.

10. 3 will be outputted because length is declared as a const in the body of the function and so has a scope of the whole function. Thus, it can be accessed in line 12.

11. An array of values [ 50, 100, 150 ] will be returned. This is because the final price after each iteration of elements in prices is pushed to a const array declared at the started of the function (as seen in line 8) which has a scope of the whole function and so can be accessed throughout.  It is also important to note that pushing elements to a const array is allowed and that const disallows reassignment or redeclaration.

# Data Types
12. 
    A.  student.name
    B.  student['Grad Year]
    C.  student.greeting()
    D.  student['Favorite Teacher'].name
    E.  student.courseLoad[0]

# Basic Operators & Type Conversion
13. 
    A.  '32' : integers map to their exact string representation so 2 is treated as a string
    B.  1 : 3 is converted to an integer an an arithmetic subtraction is performed
    C.  3 : null is treated as a 0 and so arithemtic addition is performed to 0
    D.  '3null' : null is treated as a string and so string concatenation is performed.
    E.  4 : true maps to 1 and so arithemtic addition is performed.
    F.  0 : false maps to the integer 0 and null is treated as 0 and addition is performed.
    G.  '3undefined' : undefined is converted as a string and string concatenation is performed.
    H.  NaN : not a number because the number 3 cant be subtracted by undefined.

14. 
    A.  true : 2 is converted to an integer which is greater than 1
    B.  false: false because strings are compared by the order of their characters. In this case, 2 is greater than 1 so false is returned.
    C.  true: 2 is converted to an int and 2 == 2 is true.
    D.  false : strict equality check compares data types and the first 2 is an int while the second is a string so false.
    E.  false: true maps to the integer 1 and 1 == 2 is false.
    F.  true: strict equality check compares that both are boolean types which is true.

15. == checks if the values converted to numbers by the operator are equal, whereas === also compares if the data types are the same.

# Loops
16. part2-question16.js

# Functions
17. The array [2, 4, 6] will be returned. This is because the modifyArray is called with the array [1,2,3]. Then, for each element in the array, the callback function defined as doSomething is then called and the result of this function (which multiplies the element by 2) is then pushed to the newArr and finally returned after all iterations are done. 
    
18. part2-question18.js
    
19. 1 4 3 2