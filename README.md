# Unexpected Mutable Variable Behavior in F#

This repository demonstrates a potential issue in F# related to mutable variables.  The `bug.fs` file shows how using mutable variables within a function, without creating copies of the data, can lead to unexpected results if the variables are modified after the initial function call.

The `bugSolution.fs` file provides a corrected version of the code, showcasing how to avoid this issue using immutability or explicit copying.