# F# Mutable Variable Swap Bug

This example demonstrates a common error in F# when working with mutable variables and passing them to functions.

The `swap` function attempts to swap the values of `x` and `y`, but due to F#'s pass-by-reference semantics for mutable variables, the original variables are directly modified, leading to unexpected results.

The solution shows how to correctly swap the values using a tuple return type.