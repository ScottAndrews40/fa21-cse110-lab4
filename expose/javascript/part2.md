#1 The length of the array prices will be printed because var acts like a global varial and is not bound by blocks
#2 The value asigned to discountedPrice will be printed. This is again because var is not bound by code blocks and posesses a global scope
#3 The value asigned to finalPrice will be printed. This is again because var is not bound by code blocks and posesses a global scope
#4 An array of the original prices and final prices will be returned because of vars scope and the fact that push appends and lengthens the array
#5 ReferenceError: phrase is not defined, Because let does not have scope outside of the block in which it is defined. so after the loop excutes i is undefined.
#6 