# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid index range.  The `bugSolution.java` file provides a corrected version.

## Bug Description

The bug arises from attempting to access index 5 of an array that only has indices 0-4 (length 5).  This results in an `ArrayIndexOutOfBoundsException` being thrown at runtime.

## Solution

The solution involves carefully checking the array bounds before attempting to access elements.  The corrected code verifies the index is within the valid range before accessing the array element.