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
#11 the empty array iscounted will be returned because const does not allow for reassignment.
#12 A) student.name
    B) student['Grad Year]
    C) student.greeting()
    D) student[Favorite Teacher].name
    E) student.courseload[0]