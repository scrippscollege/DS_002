# Prof. Goodwin's DS_002 repository

This example of a GitHub respository to use in Deepnote will be loaded with code following "Data Science from Scratch" by Joel Grus.

## API

### dgoodwin.linear_algebra

```
FUNCTIONS
    add(v: List[float], w: List[float]) -> List[float]
        Adds corresponding elements
    
    distance(v: List[float], w: List[float]) -> float
    
    dot(v: List[float], w: List[float]) -> float
        Computes v_1 * w_1 + ... + v_n * w_n
    
    get_column(A: List[List[float]], j: int) -> List[float]
        Returns the j-th column of A (as a Vector)
    
    get_row(A: List[List[float]], i: int) -> List[float]
        Returns the i-th row of A (as a Vector)
    
    identity_matrix(n: int) -> List[List[float]]
        Returns the n x n identity matrix
    
    magnitude(v: List[float]) -> float
        Returns the magnitude (or length) of v
    
    make_matrix(num_rows: int, num_cols: int, entry_fn: Callable[[int, int], float]) -> List[List[float]]
        Returns a num_rows x num_cols matrix
        whose (i,j)-th entry is entry_fn(i, j)
    
    scalar_multiply(c: float, v: List[float]) -> List[float]
        Multiplies every element by c
    
    shape(A: List[List[float]]) -> Tuple[int, int]
        Returns (# of rows of A, # of columns of A)
    
    squared_distance(v: List[float], w: List[float]) -> float
        Computes (v_1 - w_1) ** 2 + ... + (v_n - w_n) ** 2
    
    subtract(v: List[float], w: List[float]) -> List[float]
        Subtracts corresponding elements
    
    sum_of_squares(v: List[float]) -> float
        Returns v_1 * v_1 + ... + v_n * v_n
    
    vector_mean(vectors: List[List[float]]) -> List[float]
        Computes the element-wise average
    
    vector_sum(vectors: List[List[float]]) -> List[float]
        Sums all corresponding elements
        
```
