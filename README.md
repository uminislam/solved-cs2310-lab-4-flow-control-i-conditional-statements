Download Link: https://assignmentchef.com/product/solved-cs2310-lab-4-flow-control-i-conditional-statements
<br>
Please test the correctness of your program in <strong><u>Q  </u></strong><u>–<strong> 1, Q-2, and Q </strong>–<strong> 3 </strong></u> using PASS.

<strong>Q</strong>–<strong>1.</strong>

Write a program that reads 3 integer values (&gt;0) from the user. The 3 values are interpreted as representing the lengths of the three sides of a triangle. The program prints a message saying whether the triangle is <strong><em>Equilateral</em> </strong>(all sides equal), <strong><em>Isosceles</em></strong> (only 2 sides equal), <strong><em>Scalene </em></strong>(all sides unequal), or <strong><em>Impossible</em></strong> (can’t form a triangle). A triangle can be formed only if the sum of the length of <em>any 2</em> sides is greater than the length of the 3rd side and the length of all the sides of the triangle are<em> positive</em>.

<strong><u>Expected Output:</u></strong>

<table width="0">

 <tbody>

  <tr>

   <td width="289">Example 1</td>

   <td width="318">Example 2</td>

  </tr>

  <tr>

   <td width="289">Enter the value of A, B and C:<u>3</u><u>4</u><u>5</u>Scalene</td>

   <td width="318">Enter the value of A, B and C:<u>3</u>Equilateral</td>

  </tr>

  <tr>

   <td width="289">Example 3</td>

   <td width="318">Example 4</td>

  </tr>

  <tr>

   <td width="289">Enter the value of A, B and C:<u>2</u>Isosceles</td>

   <td width="318">Enter the value of A, B and C:<u>10</u>Impossible</td>

  </tr>

  <tr>

   <td width="289">Example 5</td>

   <td width="318">Example 6</td>

  </tr>

  <tr>

   <td width="289">Enter the value of A, B and C:<u>10</u>Impossible</td>

   <td width="318">Enter the value of A, B and C:<u>10</u>Impossible</td>

  </tr>

 </tbody>

</table>

<strong>Hint-1:</strong> If you’d like to check for equality, you should not write something like:  if (A==B==C), but instead, you should use the &amp;&amp; operator:  if (A==B &amp;&amp; B==C)

<strong>Hint-2:</strong> The <em>order</em> of checking may affect the complexity of your code <em>(although it still works)</em>. You may wish to check for impossible cases first, and identify the scalene case last.

<em>NOTE: Your program MUST follow the EXACT input/output format! Otherwise, you may not pass the test cases even though your calculation is correct.</em>

– 1 –

<em>Computer Programming </em>




<strong>Q</strong>–<strong>2.</strong>

Write a program that prompts the user to enter an integer and determines whether it is

<ul>

 <li>divisible by 3 and 5</li>

 <li>divisible by 3 only</li>

 <li>divisible by 5 only (d) not divisible by 3 or 5 <strong><u>Expected Output:</u></strong></li>

</ul>

<table width="0">

 <tbody>

  <tr>

   <td width="282">Example 1</td>

   <td width="306">Example 2</td>

  </tr>

  <tr>

   <td width="282">Enter an Integer Number: <u>15</u> 15 is divisible by 3 and 5.</td>

   <td width="306">Enter an Integer Number: <u>21</u> 21 is divisible by 3 only.</td>

  </tr>

  <tr>

   <td width="282">Example 3</td>

   <td width="306">Example 4</td>

  </tr>

  <tr>

   <td width="282">Enter an Integer Number: <u>40</u> 40 is divisible by 5 only.</td>

   <td width="306">Enter an Integer Number: <u>23</u> 23 is not divisible by 3 or 5.</td>

  </tr>

 </tbody>

</table>

<strong>Q</strong>–<strong>3.</strong>

Write a program that calculates the result of ‘a’, ‘operations’, ‘b’ which are entered by users, like ‘1+4 = 5’.

<ul>

 <li>Verify whether the input ‘a’ and ‘b’ are digits.</li>

 <li>The operations include ‘+, -, *, /, &lt;, &gt;, =’.</li>

 <li>‘True’ is simplified as ‘T’ while ‘False’ is simplified as ‘F’.</li>

 <li>When operation is ‘=’, output ‘==’ instead of ‘=’ and add brackets to the equation, e.g., (1==2)=F.</li>

</ul>

<strong><u>Expected Output:</u></strong>

<table width="0">

 <tbody>

  <tr>

   <td width="282">Example 1</td>

   <td width="306">Example 2</td>

  </tr>

  <tr>

   <td width="282">Enter the equation: <u>1</u> <u>+</u> <u>4 </u> 1+4=5</td>

   <td width="306">Enter the equation: <u>10</u> <u>/</u> <u>6 </u> 10/6=1.66667</td>

  </tr>

  <tr>

   <td width="282">Example 3</td>

   <td width="306">Example 4</td>

  </tr>

  <tr>

   <td width="282">Enter the equation: <u>a</u> <u>+</u> <u>1 </u> Invalid input.</td>

   <td width="306">Enter the equation: <u>1</u> <u>&lt;</u> <u>4 </u> 1&lt;4=T</td>

  </tr>

  <tr>

   <td width="282">Example 5</td>

   <td width="306">Example 6</td>

  </tr>

  <tr>

   <td width="282">Enter the equation: <u>1</u> <u>$</u> <u>4 </u> Invalid operation.</td>

   <td width="306">Enter the equation: <u>5</u> <u>=</u> <u>5 </u> (5==5)=T</td>

  </tr>

 </tbody>

</table>

<em>Hint: Try to use switch case! </em>