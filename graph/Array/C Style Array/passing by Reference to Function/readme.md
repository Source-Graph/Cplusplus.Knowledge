# Passing C++ arrays to function by reference
https://www.nextptr.com/question/a6212599/passing-cplusplus-arrays-to-function-by-reference

Quote:
>Array References
>There are numerous disadvantages in treating arrays as pointers. For one, it is often necessary to null-check pointers for safety protocols. Also, as pointers do not have array dimension information, they are not compatible with the modern C++ features like the range-based-for loop.
>
>Nevertheless, in C++, there is a lesser-known syntax to declare a reference to an array:

Quote:
>Passing an array to a function that takes an array by reference does not decay the array to a pointer and preserves the array size information. Moreover, we can create aliases to arrays to make their references more palatable. Here is a function that takes a 5-char array by reference with a dandy range-based-for loop:
