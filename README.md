# Off-by-one Error in Vector Access

This repository demonstrates a common off-by-one error when accessing elements in a `std::vector` in C++.  The error occurs when the loop condition incorrectly includes the index equal to the vector's size, leading to out-of-bounds access and potential crashes or undefined behavior.

The `bug.cpp` file shows the code with the error. The `bugSolution.cpp` file provides the corrected code.

This is a simple example, but the principle applies to any container with a size method or fixed-size arrays.