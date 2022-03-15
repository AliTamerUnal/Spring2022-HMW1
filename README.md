# Homework 1

In this homework you are expected to write a code to test performance of 7 different algorithms to find out if an integer value exists in a list of integers. 
Note that, functions that you implement is expected to return a boolean value.

The search algorithms that you need to implement and compare are as follows:

1. Use the list "in" operator given a list of unsorted integers
1. Use the list "in" operator given a list of sorted integers
1. Iterative search given a list of unsorted integers
1. Iterative binary search given a list of sorted integers
1. Recursive binary search given a list of sorted integers
1. Given a list of unsorted integers, sort the list and perform the iterative binary search algorithm
1. Given a list of unsorted integers, populate a set and find the integer on the set.

As an output, prepare a table (in markdown notation) where each row of to table should correspond to the performance of an algorithm with a specific list size (`n`) value.
The columns òf the table should be: Algorithm Name, `n`, Average run time per 10 runs(sec.)

Perform the test for `n` = [1000, 10000, 100000, 1000000, 10000000]

For each `n` value, generate 10 random instances, run each algorithm on each instance and record the run time. A random instance is composed of a list (say `arr`) populated by `n` random integer values in the range `[10, n * 10]`, and a random index value `x` in the range `[0, n-1]`, where `arr[x]` is the integer value that we search. Find the average of run times for each algorithm and report on the output table.

