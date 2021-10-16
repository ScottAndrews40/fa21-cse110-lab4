#1 The length of the array prices will be printed because var acts like a global varial and is not bound by blocks

#2 The value asigned to discountedPrice will be printed. This is again because var is not bound by code blocks and posesses a global scope

#3 The value asigned to finalPrice will be printed. This is again because var is not bound by code blocks and posesses a global scope

#4 An array of the original prices and final prices will be returned because of vars scope and the fact that push appends and lengthens the array

#5 ReferenceError: phrase is not defined, Because let does not have scope outside of the block in which it is defined. so after the loop excutes i is undefined.

#6 ReferenceError: phrase is not defined, because discountedPrice does not have scope outside of the for loop in which it was defined.

#7 finalPrice will be printed to the console as finalPrice has function scope.

#8 discounted will be returned because it has function scope.

#9 ReferenceError: phrase is not defined, Because let does not have scope outside of the block in which it is defined. so after the loop excutes i is undefined.

#10 The length of the array prices will be printed to console because let has function scope.

#11 the array discounted is returned

#12 A) student.name
    B) student['Grad Year]
    C) student.greeting()
    D) student[Favorite Teacher].name
    E) student.courseload[0]

#13 A) The string 32 is printed because + concatenates strings and ints
    B) The integer 1 is printed because subtraction does not behave like + with string and int data types
    C) 3+null prints the int null because null maps to zero
    D) '3'+null concatenates two strings and since '3' is a string and null is zero or a string they get concatenated as strings
    E) true+3 prints 4 because true maps to 1
    F) false+null prints 0 becasue they both map to zero
    G) '3'+undefined prints '3undefined' because it concatenates two strings
    H) '3'-undefined prints NaN because subtraction can't concatenate two strings

#14 A) This prints true because the > converts string to num and 2 is greater than 1
    B) Prints false because alphabetically 2 is greater than 12
    C) Prints true because == converts type before comparison
    D) this is false becasue === compares value and type
    E) prints false because true converts to 1 which is not 2
    F) Prints true becasue they are both boolean values 

#15 
== converts both values to the same type before comparison
=== compares the type and value of the variables or literals

#17 
The new modified array thats returned is [2,4,6]

#19
The function will print 
1 
2 
3 
4 
setTimeout() executes after the delay
