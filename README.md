# Stack Overflow Bug in JavaScript
This repository demonstrates a common error in JavaScript: stack overflow caused by unbounded recursion. The `foo` function calculates a sum recursively, but without a proper base case to stop the recursion, it leads to a stack overflow when the input `a` is large.
The solution demonstrates how to add a base case and avoid the error.  This is an important lesson in writing efficient and robust recursive functions.