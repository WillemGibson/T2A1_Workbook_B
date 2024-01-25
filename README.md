# Coder Academy T2A1-B Workbook B

### Q1: Identify and explain the workings of TWO sorting algorithms and discuss and compare their performance/efficiency.
**1. Selection Sort:**

Selection Sort is a sorting algorithm used in mainly computer science. It works by finding the lowest value in the array and moving it straight to the top, then repeating this process until the array has been fully sorted. It is a simple algorithm to understand and works in quadratic time (aka O(n^2)), making it very inefficient for larger data sets but fantastic for smaller ones.

The advantages of using Selection sort are as follows:
- Selection sort is simple and easy to understand
- Efficient on smaller data sets

The disadvantages of Quicksort are as follows:
- It has a quadratic time complexity in almost all cases
- Inefficient on larger data sets
- It is unstable. Meaning it does not preserve the relative order of items with equal keys.

![Selection Sort Animation](/Selection-Sort-Animation.gif) 

*Selection sort animation. Red is current min. Yellow is sorted list. Blue is current item.*

**2. Quicksort:**

Quicksort is an all-purpose sorting algorithm created by computer scientist Tony Hoare in 1959. The method uses a divide-and-conquer strategy to sort and what makes the algorithm so unique is its use of a pivot element that is used to create sub-arrays that are sorted recursively. This means that quicksort doesn't necessarily need to be split in half and can you used with any ratio. This makes Quicksort a somewhat efficient tool for sorting with recorded outputs between logarithmic time (aka. O(n log n)) to quadratic (aka O(n^2)) on its worst days.

The advantages of using Quicksort are as follows:
- Quicksort is usually much faster than most other algorithms which makes it a fantastic choice for larger datasets.
- It uses an in-place sorting algorithm leaving plenty of remove in the RAM for other projects.

The disadvantages of Quicksort are as follows:
- Quicksort does have a record of a quadratic time complexity making it sometimes very inefficient if the pivot element was a bad choice.
- Other sorting algorithms such as merge and heaps sorting will always be more efficient than Quicksort and easier to implement.

![Quicksort Animation](/Sorting_quicksort_anim.gif) 

*Animated visualization of the quicksort algorithm. The horizontal lines are pivot values.*

*319 words

### Q2: Identify and explain the workings of TWO search algorithms and discuss and compare their performance/efficiency.



### References:
- https://en.wikipedia.org/wiki/Selection_sort
- https://en.wikipedia.org/wiki/Quicksort
- https://www.geeksforgeeks.org/selection-sort/
- 
- https://www.youtube.com/watch?v=RfXt_qHDEPw
