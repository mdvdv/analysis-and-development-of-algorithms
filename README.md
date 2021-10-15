<h1>ANALYSIS AND DEVELOPMENT OF ALGORITHMS</h1>
<hr></hr>

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
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/constant_function.png'></td>
<td><center><formula>O(1)</formula></center></td>
</tr>
<tr>
<td>Sum of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/sum_function.png'></td>
<td><center><formula>O(n)</formula></center></td>
</tr>
<tr>
<td>Product of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/product_function.png'></td>
<td><center><formula>O(n)</formula></center></td>
</tr>
<tr>
<td>Direct Calculation of the Polynomial</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/naive_function.png'></td>
<td><center><formula>O(n*log(n))</formula></center></td>
</tr>
<tr>
<td>Horner’s Calculation of the Polynomial</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/horner_function.png'></td>
<td><center><formula>O(n*log(n))</formula></center></td>
</tr>
<tr>
<td>Bubble Sort of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/bubblesort_function.png'></td>
<td><center><formula>O(1)</formula></center></td>
</tr>
<tr>
<td>Quick Sort of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/quicksort_function.png'></td>
<td><center><formula>O(n^2)</formula></center></td>
</tr>
<tr>
<td>Timsort of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/timsort_function.png'></td>
<td><center><formula>O(n*log(n))</formula></center></td>
</tr>
<tr>
<td>Matrix Product of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/matmul_function.png'></td>
<td><center><formula>O(n^3)</formula></center></td>
</tr>
<tr>
<td>Dot Product of the Elements</td>
<td><img src='https://github.com/mdvdv/analysis-and-development-of-algorithms/blob/main/TASK%201.%20EXPERIMENTAL%20TIME%20COMPLEXITY%20ANALYSIS/images/dot_function.png'></td>
<td><center><formula>O(n^3)</formula></center></td>
</tr>
</table>

<a name='002'></a>
<h2>TASK 2. ALGORITHMS FOR UNCONSTRAINED NONLINEAR OPTIMIZATION. DIRECT METHODS</h2>

<h3>Goal</h3>

The use of direct methods (one-dimensional methods of exhaustive search, dichotomy, golden section search; multidimensional methods of exhaustive search, Gauss (coordinate descent), Nelder-Mead) in the tasks of unconstrained nonlinear optimization.

<h3>Results</h3>
