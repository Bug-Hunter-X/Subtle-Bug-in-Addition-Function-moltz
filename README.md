# Subtle Bug in Addition Function

This repository demonstrates a common, yet subtle bug in JavaScript involving the handling of zero values in an addition function.

## The Bug

The `foo` function is designed to add two numbers together. However, it contains a bug that causes it to return 0 if either of the inputs is 0, even if the other input is non-zero. This unexpected behavior might lead to issues in applications where this function is used.

## Solution

The solution involves correcting the conditional statement to accurately handle cases where only one input is 0.  The corrected function should only return 0 if both inputs are 0.