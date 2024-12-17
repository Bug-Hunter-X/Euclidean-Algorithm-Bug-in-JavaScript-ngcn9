# Euclidean Algorithm Bug

This repository demonstrates a common bug that can occur when implementing the Euclidean algorithm for finding the greatest common divisor (GCD) of two numbers. The original code contains a flaw that causes incorrect results in specific scenarios. The solution file provides a corrected version of the algorithm.

## Bug Description

The `foo` function attempts to recursively calculate the GCD using the Euclidean algorithm.  The bug occurs due to an improper handling of cases where the recursive calls approach a zero value.