# Type Mismatch Error in Swift Function Call

This repository demonstrates a common type mismatch error in Swift and its solution.  The `calculateArea` function expects `Double` values for both width and height, but the example usage attempts to pass a `String` for height. This results in a compile-time error because Swift's strong typing system prevents implicit type conversions.

The solution involves explicitly converting the String to a Double using `Double()` before passing it to the function. This ensures type safety and prevents runtime crashes.