# This repository contains my code for various algorithms written in C++

# Insertion Sort
- Starting at arr[1] and its later, check with its previous if it's smaller. If so, then switch
- Much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

Example:

5 1 6 2 4 3  // arr[1], which is 1, is smaller than arr[0], so it will be switched.

1 5 6 2 4 3  // continue with arr[2], which is 6. Nothing will happen

1 5 6 2 4 3  // continue with arr[3], which is 2, it will be moved over

1 2 5 6 4 3... and so on until it's totally sorted
  
# Merge Sort (Divide and Conquer method)
- More efficient than Insertion

Example:

(5, 9, 6, 2) 
  
(5,9), (6,2) 
  
(5), (9) ||| (6), (2) 

(5), (9) ||| (2), (6)

(5,9), (2,6)

(2,5,6,9)
