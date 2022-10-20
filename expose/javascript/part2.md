# Part 2 JS
1. Prints "2" because i goes up to prices.length which is 2, and since i is variable type var, it has function scope.
2. Prints "150" because discountedPrice will end at when prices[i] = 300 and times (1-0.5) = 150. 
3. prints "150" since discountedPrice is an integer, multiplying by 100 and dividing by 100 does nothing to original value. 
4. The function returns the list "[50, 100, 150]" because discounted gets pushed a new price every for loop which would be 50, 100, 150
5. Produces an error because i is a "let" which scope is in the for loop. Since console.log(i) is outside of it, i effectively doesn't exist for console log. 
6. Error because discountedPrice's scope is in the for loop, since console.log is outside of the for loop, discountedPrice is undeclared for it. 
7. Prints "150" because finalPrice's scope is throughout the function block. 
8. Returns [50,100,150] because discounted's scope is in the function block and thus the for loop proceeds normally.
9. Error because i's scope is in the for loop and console.log(i) is outside of it. 
10. Prints "3" because length is length's scope is the entire function. 
11. Returns "[50, 100, 150]" because when discount is being pushed, discount is still "pointing" towards the same object as before, the object itself is just updating values.  
12. 
    1. A): student.name
    2. B): student['Grad Year']
    3. C): student.greeting()
    4. D): student['Favorite Teacher'].name
    5. E): student.courseLoad[0]
13. 
    1.  A): '32'
    2.  B): 1
    3.  C): 3
    4.  D): '3null'
    5.  E): 4
    6.  F): 0
    7.  G): '3undefined'
    8.  H): NaN
14. d
    1.  A): true
    2.  B): false
    3.  C): true
    4.  D): false
    5.  E): false
    6.  F): true
15. Say if you have a == b, then == converts a and b into numbers then compare. The === operator doesn't do a type conversion, just a comparison. 
17. The result would be [2,4,6] because when we get to line 4, we get the value of array[i] and take the value as an argument for the doSomething function. The doSomething function gets called and returns num*2. The number gets pushed into the newArr. We do this for every element of the array. 
19. 1, 4, 3, 2

    