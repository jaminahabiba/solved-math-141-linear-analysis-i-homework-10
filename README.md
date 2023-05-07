Download Link: https://assignmentchef.com/product/solved-math-141-linear-analysis-i-homework-10
<br>
<ol>

 <li>(a) Finish the last page of the worksheet used in class on Monday, Oct. 28 titled ”Invertible Linear Transformations and Matrices”. Explain your reasoning for each part by making connection to ”<em>L<sub>A </sub></em>being one-to-one and onto”.</li>

</ol>

(b) Explain why a matrix has to be square in order to be invertible.

<ol start="2">

 <li>(<em>if you did not finish this last week</em>) (<em>Strang, </em><em>1.6, #25</em>) Suppose that <em>A </em>is a 3×3 matrix with (Row-1)+(Row2)=(Row-3).

  <ul>

   <li>Explain why cannot have a solution.</li>

   <li>Which right-hand sides might allow a solution to <em>A~x </em>=<em><sup>~</sup></em><em>b</em>?</li>

   <li>What happens to Row-3 if we perform forward elimination on <em>A</em>?</li>

   <li>Explain why each of the above three situations leads to the conclusion that <em>A </em>is not invertible? (Hint: Think in terms of the linear transformation <em>L<sub>A </sub></em>that <em>A </em>)</li>

  </ul></li>

 <li>(<em>if you did not finish this last week</em>) (<em>Strang, </em><em>1.6, #40</em>) True or False. If true, explain why. If false, <strong><em>show a concrete counterexample</em></strong>. (Hint: Use the fact that <em>A </em>is invertible if and only if the linear transformation <em>L<sub>A </sub></em>which it defines is invertible.)

  <ul>

   <li>A 4×4 matrix with a row of zeros is not invertible.</li>

   <li>A matrix with 1’s down the main diagonal is invertible.</li>

   <li>If <em>A </em>is invertible, then <em>A</em><sup>−1 </sup>is invertible.</li>

  </ul></li>

 <li>(<em>Strang, </em><em>1.6, #4</em>)

  <ul>

   <li>Prove the statement: if <em>A </em>is invertible and <em>AB </em>= <em>AC </em>then <em>B </em>= <em>C</em>.</li>

   <li>Write down example matrices <em>A </em>6= 0, <em>B</em>, and <em>C </em>satisfying <em>AB </em>= <em>AC </em>but <em>B </em>6= <em>C</em>.</li>

  </ul></li>

 <li>(<em>Optional</em>)

  <ul>

   <li>Finish the optional worksheet titled ”Inverse Matrix Formal Definition”, which introduces the formal mathematics definition of invertible matrices and explains its equivalence to requiring the matrix define an invertible linear transformation.</li>

   <li>Review the so-called Gauss-Jordan method to find inverse matrix you learned in Math 24. You may refresh your memory by watching some YouTube videos <a href="https://youtu.be/cJg2AuSFdjw">https://youtu.be/cJg2AuSFdjw</a><a href="https://youtu.be/cJg2AuSFdjw">.</a> Explain why this method is valid. More precisely, explain how we can be certain that the matrix we find is indeed the inverse matrix we seek?</li>

  </ul></li>

 <li>Draw a parallelogram whose area is 24 square units on the left grid given below. Let us call this parallelogram <em>P</em><sub>1</sub>. We are going to map your parallelogram using a linear transformation.</li>

</ol>

Let us use <em>P</em><sub>2 </sub>to denote the image of <em>P</em><sub>1 </sub>after the linear transformation <em>A</em>.

<ul>

 <li>Use the exercise we did in lecture, ”Area of a parallelogram”, as a hint to make a prediction of the area of <em>P</em><sub>2</sub>. Explain your reasoning.</li>

 <li>On the right grid, draw your <em>P</em><sub>2</sub>, the image of your <em>P</em><sub>1 </sub>after the transformation. Read off the area of your <em>P</em><sub>2 </sub>from the grid and verify your prediction.</li>

 <li>Let <em>B </em>: R<sup>2 </sup>→ R<sup>2 </sup>be the linear transformation that sends the square with vertices (0<em>,</em>0), (0<em>,</em>1), (1<em>,</em>0), and (1<em>,</em>1), to your <em>P</em><sub>1</sub>.</li>

 <li>Without writing down the matrix <em>B</em>, make a prediction of, do NOT calculate, the values of det<em>B </em>and det(<em>AB</em>). Explain your reasoning.</li>

 <li>Write down explicitly what matrix <em>B </em> Calculate the product <em>AB</em>, the determinants det<em>A</em>, det<em>B</em>, and det(<em>AB</em>). Verify your predictions.</li>

</ul>

<ol start="7">

 <li>Let us generalize the previous problem to n×n matrices <em>A </em>and <em>B</em>.

  <ul>

   <li>What do you think is the relationship among det(<em>AB</em>), det<em>A</em>, and det<em>B</em>?</li>

   <li></li>

  </ul></li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="615"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<ul>

 <li>In particular, if <em>A </em>is invertible, how are det<em>A </em>and det<em>A</em><sup>−1 </sup>related? Explain why.</li>

</ul>

<ol start="8">

 <li>The following are some very useful properties of determinant, some of which we proved the 2-by-2 case in lecture using areas. Knowing them will speed up your calculation of determinants in a lot of situations. Complete each sentence and use a 2×2 or 3×3 example to illustrate why your claim is true. No proof needed.

  <ul>

   <li>det<em>I<sub>n</sub></em><sub>×<em>n </em></sub>= (<em>I<sub>n</sub></em><sub>×<em>n </em></sub>denotes the <em>n </em>× <em>n </em>identity matrix).</li>

   <li>The determinant when two rows of the matrix are exchanged.</li>

   <li>If two rows of <em>A </em>are equal, then det<em>A </em>.</li>

   <li>Subtracting a multiple of one row from another row of the matrix leaves the determinant .</li>

   <li>If <em>A </em>has a row of zeros, then det<em>A </em>= .</li>

  </ul></li>

</ol>

<em>k</em>.

is a diagonal matrix, then det<em>A </em>=                         .

<ul>

 <li>If <em>A </em>is a triangular (either upper or lower) matrix, then det<em>A </em>= .</li>

 <li>If <em>A </em>is singular (i.e., not invertible), det<em>A </em>. If <em>A </em>is invertible, det<em>A</em></li>

 <li>det(<em>AB</em>) = . As a consequence, if <em>A </em>is invertible, then det<em>A </em>. (Same as previous problem, included here for the sake of completeness.)</li>

 <li>det(<em>A<sup>T</sup></em>) = .</li>

</ul>

<ol start="9">

 <li>Calculate the following determinant using Gaussian elimination. To make calculation by hand easier, you may use row-exchanges that we do not use in our <em>standard </em>forward Gaussian elimination process.</li>

</ol>

<table width="105">

 <tbody>

  <tr>

   <td width="49">4det121</td>

   <td width="20">4201</td>

   <td width="18">4010</td>

   <td width="17">41<sub></sub>22</td>

  </tr>

 </tbody>

</table>


