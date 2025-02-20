# Swift Type Mismatch Example

This repository demonstrates a common error in Swift: type mismatches in function arguments. The example showcases how passing an incorrect data type to a function leads to compilation errors.

The `bug.swift` file contains the code with the error, and the `bugSolution.swift` file provides the corrected code.

## How to reproduce:

1. Clone this repository.
2. Open `bug.swift` in Xcode.
3. Attempt to compile the code. You'll encounter a compiler error due to the type mismatch.  
4. Examine `bugSolution.swift` to see the corrected code.

## Lesson Learned

Swift's strong type system is designed to catch these kind of errors at compile time, preventing runtime crashes and unexpected behavior. Always ensure the data types of your function arguments match the function's expected parameters.