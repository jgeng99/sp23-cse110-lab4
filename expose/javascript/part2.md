<ol>
  <li> What will happen at line 12 and why? If the code causes an error, explain why. </li>
  <p> <br> It is going to print the index that is equal to the length of the prices list. First this code would not crash because i is a variable of type "var" and would be accessible anywhere in the function. i would be printed as the length of the prices list further because, when i is incrementally assigned to be the list length, it would not satisfy the condition of the for loop and would immediately exit the loop. In our example i is 3. </p>
  <li> What will happen at line 13 and why? If the code causes an error, explain why. </li>
  <p> <br> The 13th line would print "150" to the terminal. First the code would not crash because the variable "discountedPrice" is of the type "var," which would be accessible across the function. The line would print "150" because the variable is last updated when the index i accesses the last element of the prices list. In our example it would be 300. Then, "discountedPrice" is assigned to be half of the price, which is 150. </p>
  <li> What will happen at line 14 and why? If the code causes an error, explain why. </li>
  <p> <br> The 14th line would print "150" to the terminal. First the code would not crash because the variable "finalPrice" is of the type "var," which would be accessible across the function. The line would print "150" because it is just round the result of "discountedPrice" for each iteration. At the last iteration when "discountedPrice" is 150, "finalPrice" would also be 150. </p>
  <li> What will this function return? Give a brief explanation why. If the code causes an error, explain why. </li>
  <p> <br> The function would return a list of prices where each price would be half the value from the same position of the oritinal prices list. The function would return such a list because it runs through a prices list and half each price to append it to a new list. Lastly it just returns the halved prices list. </p>
  <li> What will happen at line 12 and why?  If the code causes an error, explain why. </li>
  <p> <br> There is a ReferenceError where it says the variable "i" is not defined. This is mainly because "i" is of type let defined within the for loop, and the variable type "let" is block-scoped that would not be accessible outside of the  block. </p>
  <li> What will happen at line 13 and why? If the code causes an error, explain why. </li>
  <p> <br> There is a ReferenceError where it says the variable "discountedPrice" is not defined. This is mainly because "discountedPrice" is of type let defined within the for loop, and the variable type "let" is block-scoped that would not be accessible outside of the block. </p>
  <li> What will happen at line 14 and why? If the code causes an error, explain why. </li>
  <p> <br> The 14th line would print "150" to the terminal. First the code would not crash because the variable "finalPrice" is as the type "let" at the very top of the function, which will be accessible across the function block. The line would print "150" because it is just round the result of "discountedPrice" for each iteration. At the last iteration when "discountedPrice" is 150, "finalPrice" would also be 150. </p>
  <li> What will this function return? Give a brief explanation. If the code causes an error, explain why. </li>
  <p> <br> The function will return a list of prices where each price is half the value from the same position of the oritinal prices list. The function first returns successfully because the initialization and return of the variable are within the same block. The function further returns such a halved prices list because it runs through a prices list and half each price to append it to a new list. Lastly it just returns the halved prices list. </p>
  <li> What will happen at line 11 and why? If the code causes an error, explain why. </li>
  <p> <br> There is a ReferenceError where it says the variable "i" is not defined. This is mainly because "i" is of type let defined within the for loop, and the variable type "let" is block-scoped that would not be accessible outside of the  block. </p>
  <li> What will happen at line 12 and why? If the code causes an error, explain why. </li>
  <p> <br> The 12th line would print "3" to the terminal. First the code would not crash because the variable "length" is defined as the type "const" at the very top of the function, which will be accessible across the function block. The line prints "3" because it is the size of the input list. </p>
  <li> What will this function return? Give a brief explanation. If the code causes an error, explain why. </li>
  <p> <br> The function will return a list of prices where each price is half the value from the same position of the oritinal prices list. The function first returns successfully because the initialization and return of the variable are within the same block. This is in accordance to the definition of a const type. The function further returns such a halved prices list because it runs through a prices list and half each price to append it to a new list. We are able to append to the const type because we are not assigning it to a new value. Lastly it just returns the halved prices list. </p>
  <li> 
    Given the above Object, write the notation for: 
    <br> &nbsp;&nbsp; A. Accessing the value of the name property in the student object 
    <p> <br> &nbsp;&nbsp;&nbsp; student['name'] </p>
  </li>
</ol>