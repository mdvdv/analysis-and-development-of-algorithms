<h1>ANALYSIS AND DEVELOPMENT OF ALGORITHMS</h1>
<hr></hr>

Author: <a href='https://github.com/mdvdv'>Anatolii Medvedev</a>

Group: J4133c

<a name='000'></a>
<h2>CONTENT</h2>

<ul>
    <ol type='1'>
    <li><a href='#001'>TASK 1. EXPERIMENTAL TIME COMPLEXITY ANALYSIS</a></li>
    <li><a href='#002'>TASK 2. ALGORITHMS FOR UNCONSTRAINED NONLINEAR OPTIMIZATION. DIRECT METHODS</a></li>
    </ol>
</ul>

<a name='001'></a>
<h2>TASK 1. EXPERIMENTAL TIME COMPLEXITY ANALYSIS</h2>

<h3>Goal</h3>

Experimental study of the time complexity of different algorithms.

<h3>Results</h3>

<table>
<tr>
<th>Algorithm Name</th>
<th>Empirical Time Complexity</th>
<th>Theoretical Time Complexity</th>
</tr>
<tr>
<td>Constant Function</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/constant_function.png'></td>
<td align='center'><formula>O(1)</formula></td>
</tr>
<tr>
<td>Sum of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/sum_function.png'></td>
<td align='center'><formula>O(n)</formula></td>
</tr>
<tr>
<td>Product of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/product_function.png'></td>
<td align='center'><formula>O(n)</formula></td>
</tr>
<tr>
<td>Direct Calculation of the Polynomial</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/naive_function.png'></td>
<td align='center'><formula>O(n*log(n))</formula></td>
</tr>
<tr>
<td>Horner’s Calculation of the Polynomial</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/horner_function.png'></td>
<td align='center'><formula>O(n*log(n))</formula></td>
</tr>
<tr>
<td>Bubble Sort of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/bubblesort_function.png'></td>
<td align='center'><formula>O(n^2)</formula></td>
</tr>
<tr>
<td>Quick Sort of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/quicksort_function.png'></td>
<td align='center'><formula>O(n*log(n))</formula></td>
</tr>
<tr>
<td>Timsort of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/timsort_function.png'></td>
<td align='center'><formula>O(n*log(n))</formula></td>
</tr>
<tr>
<td>Matrix Product of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/matmul_function.png'></td>
<td align='center'><formula>O(n^3)</formula></td>
</tr>
<tr>
<td>Dot Product of the Elements</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/dot_function.png'></td>
<td align='center'><formula>O(n^3)</formula></td>
</tr>
</table>

<a name='002'></a>
<h2>TASK 2. ALGORITHMS FOR UNCONSTRAINED NONLINEAR OPTIMIZATION. DIRECT METHODS</h2>

<h3>Goal</h3>

The use of direct methods (one-dimensional methods of exhaustive search, dichotomy, golden section search; multidimensional methods of exhaustive search, Gauss (coordinate descent), Nelder-Mead) in the tasks of unconstrained nonlinear optimization.

<h3>Results</h3>

<table>
<tr>
<th>Function Name</th>
<th>Algorithm Name</th>
<th>Function Minimization Graph</th>
<th>x</th>
<th>f(x)</th>
<th>Number of iterations</th>
</tr>
<tr>
<td>Cubic Function</td>
<td>Exhaustive Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/cubic_function.png'></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>1001</formula></td>
</tr>
<tr>
<td>Cubic Function</td>
<td>Dichotomy Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/cubic_function.png'></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>11</formula></td>
</tr>
<tr>
<td>Cubic Function</td>
<td>Golden Section Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/cubic_function.png'></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>15</formula></td>
</tr>
<tr>
<td>Absolute Value Function</td>
<td>Exhaustive Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/absolute_function.png'></td>
<td align='center'><formula>0.2</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>1001</formula></td>
</tr>
<tr>
<td>Absolute Value Function</td>
<td>Dichotomy Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/absolute_function.png'></td>
<td align='center'><formula>0.2</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>11</formula></td>
</tr>
<tr>
<td>Absolute Value Function</td>
<td>Golden Section Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/absolute_function.png'></td>
<td align='center'><formula>0.2</formula></td>
<td align='center'><formula>0.0</formula></td>
<td align='center'><formula>15</formula></td>
</tr>
<tr>
<td>Sine Function</td>
<td>Exhaustive Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/sine_function.png'></td>
<td align='center'><formula>0.223</formula></td>
<td align='center'><formula>-0.217</formula></td>
<td align='center'><formula>991</formula></td>
</tr>
<tr>
<td>Sine Function</td>
<td>Dichotomy Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/sine_function.png'></td>
<td align='center'><formula>0.223</formula></td>
<td align='center'><formula>-0.217</formula></td>
<td align='center'><formula>11</formula></td>
</tr>
<tr>
<td>Sine Function</td>
<td>Golden Section Search</td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/sine_function.png'></td>
<td align='center'><formula>0.223</formula></td>
<td align='center'><formula>-0.217</formula></td>
<td align='center'><formula>15</formula></td>
</tr>

<table>
<tr>
<th>Minimization of Linear Approximating Function</th>
<th>Minimization of Rational Approximating Function</th>
</tr>
<tr>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/linear_approximant.png'></td>
<td bgcolor=white><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%202.%20ALGORITHMS%20FOR%20UNCONSTRAINED%20NONLINEAR%20OPTIMIZATION.%20DIRECT%20METHODS/images/rational_approximant.png'></td>
</tr>
<tr>
<td><formula>Exhaustive Search</formula></td>
<td align='center'><formula>(0.871, 0.404)</formula></td>
<td align='center'><formula>(0.473, -0.716)</formula></td>
</tr>
<tr>
<td><formula>Gauss Search</formula></td>
<td align='center'><formula>(0.871, 0.404)</formula></td>
<td align='center'><formula>(0.835, 0.0)</formula></td>
</tr>
<tr>
<td><formula>Nelder-Mead Search</formula></td>
<td align='center'><formula>(0.871, 0.404)</formula></td>
<td align='center'><formula>(0.473, -0.716)</formula></td>
</tr>