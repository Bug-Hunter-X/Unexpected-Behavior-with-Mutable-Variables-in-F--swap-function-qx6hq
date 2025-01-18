# F# Mutable Variable Bug

This repository demonstrates a common issue in F# related to mutable variables and unexpected side effects within functions.

The `bug.fs` file contains code that attempts to swap two mutable variables using a function. However, due to how mutable variables are handled in F#, the global variables are modified, leading to unexpected results.

The `bugSolution.fs` file provides a corrected version of the code, showcasing how to avoid such issues by using techniques that avoid unexpected side effects and maintain referential transparency whenever possible.