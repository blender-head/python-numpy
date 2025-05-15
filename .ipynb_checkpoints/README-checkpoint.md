NumPy (Numerical Python) is a fundamental Python library for scientific computing and numerical operations. It provides support for large, multi-dimensional arrays and matrices, along with a vast collection of high-level mathematical functions to operate on these arrays efficiently.

## Key Features of NumPy:

1. ndarray (N-dimensional array):
    - NumPy's core feature is the ndarray, a fast and memory-efficient array object for handling large datasets.
    - Supports vectorized operations (eliminating the need for loops).

2. Mathematical Functions:
    - Provides linear algebra, Fourier transforms, random number generation, and more.
    - Optimized for performance (written in C and Fortran).

3. Broadcasting:
    - Allows operations on arrays of different shapes.

4. Interoperability:
    - Works well with other libraries like Pandas, SciPy, Matplotlib, TensorFlow, and PyTorch.

5. Memory Efficiency:
    - Uses contiguous memory blocks, making it faster than Python lists.
  
## Tutorial Source

[Numpy Full Course](https://www.youtube.com/watch?v=8Y0qQEh7dJg)

## File List
- `00_numpy_intro.ipynb`:
    - NumPy introduction
- `01_creating_arrays.ipynb`:
    - NumPy array definition
    - Understanding Dimensions in Arrays
    - Create Array Using `arange`
    - Create Array Using `linspace`
    - Creating Array Using `zeros`
    - Creating Array Using `ones`
    - Get Array Size
    - Create Array Using `random`
- `03_slicing_and_indexing.ipynb`:
    - Basic Indexing
    - Slicing Array
    - Advanced Indexing
    - Key Differences Between Indexing & Slicing
    - Notes on Slicing and Indexing
- `04_shaping_arrays.ipynb`:
    - Array Shape concept
    - Check array shape using `shape`
    - Reshape an array using `reshape`
    - Flatten an array using `flatten`
    - Resize an array using `resize`
    - Transpose an array using `transpose` and `ndarray.T attribute`
    - Swap axes an array `swapaxes`
- `05_stacking_and_splitting.ipynb`:
    - Stacking array using:
        - `stack`
        - `vstack`
        - `dstack`
    - Splitting array using:
        - `split`
        - `vsplit`
        - `hsplit`
        - `dsplit`
    - Real-World Applications of Stacking and Splitting Arrays in NumPy
- `copying_array.ipynb`:
    - Copying array using:
        - `copy`
        - `np.copy`
- `07_basic_math.ipynb`:
    - Arithmetic Operations using :
        - `add`
        - `subtract`
        - `multiply`
        - `divide`
        - `power`
        - `sqrt`
        - `sin`
        - `sbs`
    - Aggregation Operations using:
        - `sum`
        - `min`
        - `max`
        - `mean`
        - `std`
        - `argmax`
    - Matrix Operations using:
        - `dot`
    - Cumulative Sum using:
        - `cumsum`
    - Logarithmic Operations using:
        -  `log`
        -  `log2`
        -  `log10`
    - Greatest Common Divisor (GCD) using:
        - `gcd.reduce`
    - Least Common Multiple (LCM) using:
        - `lcm.reduce`
    - Rounding Functions using:
        - `ceil`
        - `floor`
- `08_numpy_and_panda.ipynb`:
    - todo
- `09_statistic_functions.ipynb`:
    - Calculate mean using `mean`
    - Calculate median using `median`
    - Calculate variance using `var`
    - Calculate standard deviation using `std`
    - Calculate minimun using `min`
    - Calculate maximum using `max`
    - Calculate product using `prod`
    - Calculate quantiles using `quantile`
    - Calculate correlation using `corrcoef`
    - Calculate covariance using `cov`
    - Create histogram using `histogram` and `histogram2d`
    - Calculate convolution using `convolve`
- `10_trigonometric_functions.ipynb`:
    - Basic Trigonometric Functions:
        - `sin`
        - `cos`
        - `tan`
    - Inverse Trigonometric Functions:
        - `arcsin`
        - `arccos`
        - `arctan`
        - `arctan2`
    - Hyperbolic Trigonometric Functions:
        - `sinh`
        - `cosh`
        - `tanh`
    - Angle Conversion Functions:
        - `deg2rad`
        - `rad2deg`
- `11_matrix_functions.ipynb`:
    - Matrix Creation:
        - `numpy.array()`
        - `numpy.matrix()`
        - `numpy.eye()`
        - `numpy.zeros()`
        - `numpy.ones()`
    - Matrix Operations:
        - `numpy.dot()`
        - `numpy.transpose()` or `.T`
        - `numpy.linalg.inv()`
        - `numpy.linalg.det()`
        - `numpy.trace()`
        - `numpy.linalg.multi_dot`
    - Eigenvalues & Eigenvectors:
        - `numpy.linalg.eig()`
        - `numpy.linalg.eigvals()`
    - Matrix Decomposition:
        - `numpy.linalg.svd()`
        - `numpy.linalg.qr()`
        - `numpy.linalg.cholesky()`
    - Solving Linear Equations:
        - `numpy.linalg.solve()`
        - `numpy.linalg.lstsq()`
    - Matrix Norms:
        - `numpy.linalg.norm()`
    - Matrix Exponentiation
        - `numpy.linalg.matrix_power()`   
- `12_saving_and_loading.ipynb`:
    - Saving NumPy Object using `save`
    - Loading Numpy Object using `load`
    - Saving Numpy Object as CSV using `savetxt`
    - Loading CSV file `loadtxt`
- `13_numpy_financial.ipynb`:
    - Install numpy_financial library `pip install numpy-financial` 
    - Calculates the future value of an investment using `fv` function
    - Calculates the present value of an investment using `pv` function
    - Calculates the payment for a loan using `pmt` function
    - Calculates the net present value of a cash flow series using `npv` function
    - Calculates the internal rate of return for a series of cash flows using `irr` function
    - Calculates the number of periods for an investment using `nper` function
    - Calculates the interest rate per period using `rate`function
- `14_comparison_functions.ipynb`:
    - Comparison Functions:
        - `numpy.equal` or `==`
        - `numpy.not_equal` or `!=`
        - `numpy.greater` or `>`
        - `numpy.greater_equal` or `>=`
        - `numpy.less` or `<`
        - `numpy.less_equal` or `<=`
        - `numpy.array_equal`
        - `numpy.logical_and`
        - `numpy.logical_or`
        - `numpy.logical_not`
        - `numpy.isclose`