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
    <p> &emsp;&emsp;&emsp; student['name'] </p>
    &nbsp;&nbsp; B. Accessing the value of the Grad Year property in the student object
    <p> &emsp;&emsp;&emsp; student['Grad Year'] </p>
    &nbsp;&nbsp; C. Calling the function for the greeting property in the student object
    <p> &emsp;&emsp;&emsp; student['greeting']() </p>
    &nbsp;&nbsp; D. Accessing the name property of the object in the Favorite Teacher property in student
    <p> &emsp;&emsp;&emsp; student['Favorite Teacher']['name'] </p>
    &nbsp;&nbsp; E. Access index zero in the array of the courseLoad property of the student object
    <p> &emsp;&emsp;&emsp; student['courseLoad'][0] </p>
  </li>
  <li> Arithmetic
    <br> &nbsp;&nbsp; A. ‘3’ + 2
    <p> &emsp;&emsp;&emsp; The output is "32". This is because it will cast int to string before the addition. </p>
    <br> &nbsp;&nbsp; B. ‘3’ - 2
    <p> &emsp;&emsp;&emsp; The output is 1. This is because it will cast string to int before the subtraction. </p>
    <br> &nbsp;&nbsp; C. 3 + null
    <p> &emsp;&emsp;&emsp; The output is 3. This is because the addition operator will treat null as 0 with another integer. </p>
    <br> &nbsp;&nbsp; D. ‘3’ + null
    <p> &emsp;&emsp;&emsp; The output is '3null'. This is because the addition operator will treat null as a string with another string. </p>
    <br> &nbsp;&nbsp; E. true + 3
    <p> &emsp;&emsp;&emsp; The output is 4. This is because the addition operator will treat true as 1 with another integer. </p>
    <br> &nbsp;&nbsp; F. false + null
    <p> &emsp;&emsp;&emsp; The output is 0. This is because the addition operator will treat false and null as 0 in numeric operations. </p>
    <br> &nbsp;&nbsp; G. '3' + undefined
    <p> &emsp;&emsp;&emsp; The output is '3undefined'. This is because the addition operator will convert undefined value to string and concatenate it with '3'. </p>
    <br> &nbsp;&nbsp; H. '3' - undefined
    <p> &emsp;&emsp;&emsp; The output is NaN. This is because the subtraction operator will first convert string to numeric value. But undefined cannot be compared to numeric value in any ways, this results in an invalid mathematical operation. </p>
  </li>
  <li> Comparison
    <br> &nbsp;&nbsp; A. '2' > 1
    <p> &emsp;&emsp;&emsp; The output is true. This is because string '2' becomes a number 2 and 2 is greater than 1. </p>
    <br> &nbsp;&nbsp; B. '2' < '12'
    <p> &emsp;&emsp;&emsp; The output is false. This is because string '2' is compared against '1', and '2' is greater than '1'. </p>
    <br> &nbsp;&nbsp; C. 2 == '2'
    <p> &emsp;&emsp;&emsp; The output is true. This is because string '2' becomes a number 2 and 2 equals to 2. </p>
    <br> &nbsp;&nbsp; C. 2 === '2'
    <p> &emsp;&emsp;&emsp; The output is false. This is because the operator === checks the equality without type conversion, and the types are different. </p>
    <br> &nbsp;&nbsp; C. true == 2
    <p> &emsp;&emsp;&emsp; The output is true. This is because boolean true becomes a number 1 and 2 is not equal 1. </p>
    <br> &nbsp;&nbsp; C. true === Boolean(2)
    <p> &emsp;&emsp;&emsp; The output is true. This is because boolean 2 is true. And === operator checks the equality without type conversion. </p>
  </li>
  <li> Explain the difference between the == and === operators. </li>
  <p> <br> Both operators are used to compare value. '==' converts operands of differents types and then check equality. '===' checks the equality without type conversion. </p>
  <li> Given the above Object, write a for...in loop that will iterate through it and print out the value of the property if the property starts with the letter r, or if the value of that property is an odd number. </li>
  <p> <br> In 'part2-question16.js' </p>
  <li> If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result. </li>
  <p> <br> The result will be an array [2,4,6]. Within the modifyArray, it takes in an array and a function, then creates a new array. After that, it iterates through the length of input array. For each iteration, it calls the function on the ith index and pushes the result to the new array. When the loop ends, it returns this new array.  </p>
  <li> The above program only prints out the time once when executed. Modify this code such that the program prints out the time every second. </li>
  <p> <br> In 'part2-question18.js' </p>
  <li> What is the output of the above code? </li>
  <p> <br> The output is 1, 4, 3, 2 in this order. </p>
</ol>