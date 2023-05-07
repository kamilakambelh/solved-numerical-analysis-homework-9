Download Link: https://assignmentchef.com/product/solved-numerical-analysis-homework-9
<br>



<ul>

 <li>To get full credit, <em>you must write down sufficient intermediate steps</em>, only giving the final answer earns you no credit!</li>

 <li>Please make sure that your handwriting is recognizable, otherwise you only get partial credit for the recognizable part.</li>

</ul>

<ol>

 <li>Simpson’s rule.

  <ul>

   <li>Show that on [−1<em>,</em>1] Simpson’s rule can be obtained as follows</li>

  </ul></li>

</ol>

<em>,</em>

where <em>y </em>∈ C<sup>4</sup>[−1<em>,</em>1] and <em>p</em><sub>3</sub>(<em>y</em>;−1<em>,</em>0<em>,</em>0<em>,</em>1;<em>t</em>) is the interpolation polynomial of <em>y </em>with interpolation conditions <em>p</em><sub>3</sub>(−1) = <em>y</em>(−1), <em>p</em><sub>3</sub>(0) = <em>y</em>(0),

(0), and <em>p</em><sub>3</sub>(1) = <em>y</em>(1).

<ul>

 <li>Derive <em>E<sup>S</sup></em>(<em>y</em>).</li>

 <li>Using (a), (b) and a change of variable, derivethe composite Simpson’s rule and prove the theorem on its error estimation.</li>

</ul>

<ol>

 <li>Estimate the number of subintervals required to ap-proximateto 6 correct decimal places, i.e. the absolute error is no greater than 0<em>.</em>5 × 10<sup>−6</sup>,

  <ul>

   <li>by the composite trapezoidal rule,(b) by the composite Simpson’s rule.</li>

  </ul></li>

</ol>

<ul>

 <li>Gauss-Laguerre quadrature formula.

  <ul>

   <li>Construct a polynomial <em>π</em><sub>2</sub>(<em>t</em>) = <em>t</em><sup>2 </sup>+ <em>at </em>+ <em>b </em>that is orthogonal to P1 with respect to the weight function <em>ρ</em>(<em>t</em>) = <em>e</em><sup>−<em>t</em></sup>, i.e.</li>

  </ul></li>

</ul>

∀<em>p </em>∈ P1<em>,          </em><em>.</em>

(<em>hint</em>:

<ul>

 <li>(10 points) Derive the two-point Gauss-Laguerrequadrature formula</li>

</ul>

and express <em>E</em><sub>2</sub>(<em>f</em>) in terms of <em>f</em><sup>(4)</sup>(<em>τ</em>) for some <em>τ &gt; </em>0.

<table width="273">

 <tbody>

  <tr>

   <td width="23">x</td>

   <td width="41">0.0</td>

   <td width="33">0.5</td>

   <td width="33">1.0</td>

   <td width="33">1.5</td>

   <td width="40">2.0</td>

   <td width="40">2.5</td>

   <td width="32">3.0</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">2.9</td>

   <td width="33">2.7</td>

   <td width="33">4.8</td>

   <td width="33">5.3</td>

   <td width="40">7.1</td>

   <td width="40">7.6</td>

   <td width="32">7.7</td>

  </tr>

  <tr>

   <td width="23">x</td>

   <td width="41">3.5</td>

   <td width="33">4.0</td>

   <td width="33">4.5</td>

   <td width="33">5.0</td>

   <td width="40">5.5</td>

   <td width="40">6.0</td>

   <td width="32">6.5</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">7.6</td>

   <td width="33">9.4</td>

   <td width="33">9.0</td>

   <td width="33">9.6</td>

   <td width="40">10.0</td>

   <td width="40">10.2</td>

   <td width="32">9.7</td>

  </tr>

  <tr>

   <td width="23">x</td>

   <td width="41">7.0</td>

   <td width="33">7.5</td>

   <td width="33">8.0</td>

   <td width="33">8.5</td>

   <td width="40">9.0</td>

   <td width="40">9.5</td>

   <td width="32">10.0</td>

  </tr>

  <tr>

   <td width="23">y</td>

   <td width="41">8.3</td>

   <td width="33">8.4</td>

   <td width="33">9.0</td>

   <td width="33">8.3</td>

   <td width="40">6.6</td>

   <td width="40">6.7</td>

   <td width="32">4.1</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Apply the formula in (b) to approximate</li>

</ul>

Use the remainder to estimate the error and compare your estimate with the true error. With the true error, identify the unknown quantity <em>τ </em>contained in <em>E</em><sub>2</sub>(<em>f</em>).

(<em>hint</em>: use the exact value <em>I </em>= 0<em>.</em>596347361···)

The above four problems weigh 15, 10, and 20 points, respectively.

<h1>2           C++ programming</h1>

Write a C++ function to perform discrete least square via QR factorization. Your algorithm should take as input the maximum degree of the fitting polynomial, three or more data pairs (<em>x<sub>i</sub>,y<sub>i</sub></em>), and output coefficients of the fitted polynomial.

Run your subroutine on the following data.

In the notes, the condition number of a matrix <em>A </em>is defined as cond<em><sub>A </sub></em>(<strong>x</strong>) = k<em>A</em>kk<em>A</em><sup>−1</sup>k<em>.</em>

Report the condition number based on the 2-norm of the matrix <em>G </em>in the normal-equation approach (reuse results of your previous homework!) and that of the matrix <em>R</em><sub>1 </sub>in the QR-factorization approach, verifying that the former is much larger than the latter.

This programming assignment weighs 10 points. Thus the total number of points is 55 for this homework.