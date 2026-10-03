# Day 14 – NumPy Matrix Operations

## AI & ML Internship – Day 14

This project demonstrates basic **matrix operations using NumPy in Python**. It covers matrix creation, addition, subtraction, element-wise multiplication, matrix multiplication, and transpose operations.

## Objective

To understand and implement fundamental matrix operations using NumPy and learn how matrices are used in Machine Learning.

## Tools & Technologies

- Python
- NumPy
- Jupyter Notebook
- GitHub

## Operations Performed

The following operations were implemented:

1. Matrix Creation
2. Matrix Addition
3. Matrix Subtraction
4. Element-wise Multiplication
5. Matrix Multiplication
6. Matrix Transpose

## Matrices Used

### Matrix A

```text
[[1 2 3]
 [4 5 6]
 [7 8 9]]
````

### Matrix B

```text
[[9 8 7]
 [6 5 4]
 [3 2 1]]
```

## Results

### 1. Matrix Addition

```text
[[10 10 10]
 [10 10 10]
 [10 10 10]]
```

Implemented using:

```python
A + B
```

### 2. Matrix Subtraction

```text
[[-8 -6 -4]
 [-2  0  2]
 [ 4  6  8]]
```

Implemented using:

```python
A - B
```

### 3. Element-wise Multiplication

```text
[[ 9 16 21]
 [24 25 24]
 [21 16  9]]
```

Implemented using:

```python
A * B
```

Element-wise multiplication multiplies corresponding elements of the two matrices.

### 4. Matrix Multiplication

```text
[[ 30  24  18]
 [ 84  69  54]
 [138 114  90]]
```

Implemented using:

```python
A @ B
```

Matrix multiplication was also performed using:

```python
np.dot(A, B)
```

Both methods produce the same result.

### 5. Matrix Transpose

Transpose of Matrix A:

```text
[[1 4 7]
 [2 5 8]
 [3 6 9]]
```

Implemented using:

```python
A.T
```

## Element-wise vs Matrix Multiplication

| Feature               | Element-wise Multiplication           | Matrix Multiplication                           |
| --------------------- | ------------------------------------- | ----------------------------------------------- |
| NumPy operator        | `*`                                   | `@`                                             |
| Operation             | Corresponding elements are multiplied | Rows are multiplied with columns                |
| Dimension requirement | Usually same-shaped arrays            | Columns of first matrix = rows of second matrix |
| Example               | `A * B`                               | `A @ B`                                         |

### Example

For:

```text
A = [[1 2]
     [3 4]]

B = [[5 6]
     [7 8]]
```

Element-wise multiplication:

```text
A * B

[[ 5 12]
 [21 32]]
```

Matrix multiplication:

```text
A @ B

[[19 22]
 [43 50]]
```

## Why Matrix Operations Are Important in Machine Learning

Matrices are fundamental to Machine Learning because data, features, weights, images, and model parameters can be represented using matrices.

Matrix operations are extensively used in:

* Linear Regression
* Neural Networks
* Deep Learning
* Computer Vision
* Data Transformation
* Feature Representation
* Model Weight Calculations

Understanding matrix operations provides a foundation for understanding how many Machine Learning algorithms process data.

## Interview Questions

### 1. What is a matrix?

A matrix is a rectangular arrangement of numbers or elements organized into rows and columns. Matrices are widely used in mathematics, data science, and machine learning.

### 2. What is the difference between element-wise and matrix multiplication?

Element-wise multiplication multiplies corresponding elements of two matrices.

Matrix multiplication follows the row-by-column multiplication rule. For matrix multiplication, the number of columns in the first matrix must be equal to the number of rows in the second matrix.

### 3. Why are matrices important in Machine Learning?

Matrices provide an efficient way to represent and process datasets, features, images, weights, and model parameters. Many Machine Learning and Deep Learning algorithms rely on matrix operations for calculations.

## Project Structure

```text
Day-14-NumPy-Matrix-Operations/
│
├── Day_14_NumPy_Matrix_Operations.ipynb
└── README.md
```

## Learning Outcomes

Through this task, I learned:

* How to create matrices using NumPy
* How to perform matrix addition and subtraction
* How to perform element-wise multiplication
* How to perform matrix multiplication using `@` and `np.dot()`
* How to transpose matrices using `.T`
* The difference between element-wise and matrix multiplication
* The importance of matrices in Machine Learning

## Conclusion

This task provided practical experience with fundamental matrix operations using NumPy. These operations form an important foundation for understanding numerical computing, Machine Learning algorithms, and Deep Learning models.

---

**AI & ML Internship – Day 14**
**Task: NumPy Matrix Operations**

```
```
