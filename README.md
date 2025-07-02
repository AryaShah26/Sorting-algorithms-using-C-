# Sorting-algorithms-using-C-
## Description  This project compares six sorting algorithms in C++ on a list of 100,000 elements. It shows how algorithm choice impacts performance, highlighting why efficient `O(N log N)` sorts like QuickSort and MergeSort outperform slower `O(N²)` methods on large datasets.
# Sorting Algorithm Performance Comparison

## Description

This project compares six sorting algorithms in C++ on a list of 100,000 elements. It shows how algorithm choice impacts performance, highlighting why efficient `O(N log N)` sorts like QuickSort and MergeSort outperform slower `O(N²)` methods on large datasets.

## Algorithms Tested

| Algorithm      | Time (seconds)  |
|----------------|------------------|
| QuickSort      | 0.021053         |
| MergeSort      | 0.023 (predicted)|
| InsertionSort  | 8.8368           |
| SelectionSort  | 11.8582          |
| ExChangeSort   | 31.4496          |
| BubbleSort     | 38.818           |

## Insights

- **QuickSort** and **MergeSort** show the best performance with `O(N log N)` time complexity.
- **InsertionSort**, **SelectionSort**, **ExChangeSort**, and **BubbleSort** are significantly slower for large datasets due to their `O(N²)` time complexity.
- The results highlight the practical impact of choosing the right algorithm for large-scale data.

## How to Run

1. Compile the program:
   ```bash
   g++ sort_comparison.cpp -o sort_comparison
