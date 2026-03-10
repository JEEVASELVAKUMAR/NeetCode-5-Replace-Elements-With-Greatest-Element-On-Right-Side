# Replace Elements with Greatest Element on Right Side

## Overview

This project implements a Java program that replaces each element in an array with the greatest element among the elements to its right. The last element of the array is replaced with **-1** since there are no elements to its right.

This problem helps in understanding **array traversal, nested loops, and basic problem-solving techniques in Java**.

## Example

Input:
arr = [2,4,5,3,1,2]

Output:
[5,5,3,2,2,-1]

Input:
arr = [3,3]

Output:
[3,-1]

## Approach

1. Traverse the array from the first element.
2. For each element, check all elements to its right.
3. Find the maximum element among them.
4. Replace the current element with that maximum value.
5. Replace the last element with **-1**.

## Concepts Used

* Arrays in Java
* Nested loops
* Maximum value comparison
* Basic algorithm design

## Learning Outcome

* Understanding array manipulation
* Implementing logic using loops
* Practicing problem-solving with Java arrays

## Author

Jeeva Selvakumar
