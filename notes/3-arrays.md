# Arrays

Simplest type of collection
- Linear (sequence structure)
- Static (fixed size, but some langues support dynamic arrays)
- Indexed (Data items accessed via one or more indexes)
- Can also have 2D Arrays (Matrices) and nD arrays

## C# Array class

```C#
// 1-dimensional array
int[] myIntArray = new int[5] { 1, 2, 3, 4, 5 } ;
```


```C#
// multi-dimensional arrays
Double[,] myDoubles = new Double[10, 20];
String[,,] myStrings = new String[5, 3, 10];
```

```C#
// jagged-dimensional arrays
int[][] jaggedInts = new int[3][] ;

jaggedInts[0] = new int[2] ;  // 1st row: 2 element array
jaggedInts[1] = new int[4] ;  // 2nd row: 4 element array
jaggedInts[2] = new int[6] ;  // 3rd row: 6 element array
```


## Searching

### Linear Search

- Brute force (Takes O(N))
- Just uses a for loop to search array going through each element

### Binary Search

- More efficient than Linear search
- Array must be sorted first
- It's a Divide & Conquer algorithm


### Complexity of Binary Search

Complexity is O(log 2 to the N)
Need to know how to derive it


## Sorting

Two types of sorting algorithms
0. Simple algorithms - Basic algorithms which are not categorized
1. Divide & Conquer - Split the work. Solve sub problems separately. Combine the solutions
2. Decrease & Conquer - Each iteration decreases the amount of work to be done

For each of the following algorithms, we need to learn:
- Characteristics
- Algorithm
- Implementation
- Complexity

### Selection Sort

### Bubble Sort

### Merge Sort

## C# Array Algorithms

