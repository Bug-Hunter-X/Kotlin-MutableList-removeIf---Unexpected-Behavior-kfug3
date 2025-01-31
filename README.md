This repository demonstrates a common yet subtle error in Kotlin when using the `removeIf()` function with mutable lists.  The example shows that modifying a list while iterating over it can lead to unexpected behavior and skipped elements.

The `bug.kt` file showcases the problem. The solution, shown in `bugSolution.kt`, illustrates the correct way to handle such scenarios.