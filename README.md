# SortingOptimization
This repository contains an example of optimizing the sorting of an array in C++ by checking if the array is already sorted before sorting it.

## Code Explanation

The code uses `std::is_sorted` to check if the array is sorted and `std::sort` to sort the array if needed. This optimization can save time when the array is already sorted.

## Compilation

To compile the code, use the following command:

```sh
g++ -std=c++11 -O2 -o sort_example sort_example.cpp


