<ol>
  <li> What was the bug? </li>
  <p> <br> The bug was that both num1 and num2 are string. So when adding them together, the add operator was doing a string addition, resulting in a concatenation of the inputs. </p>
  <li> How would you fix it? </li>
  <p> <br> I would invoke parseInt() on both num1 and num2 to convert them to integer. </p>
</ol>