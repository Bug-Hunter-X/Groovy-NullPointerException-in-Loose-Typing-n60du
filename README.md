# Groovy NullPointerException in Loose Typing

This example demonstrates a common issue in Groovy: unexpected `NullPointerException`s due to the dynamic nature of the language.  Groovy's loose typing allows you to pass `null` values to methods without explicit type checking. If the method doesn't correctly handle these nulls, it can lead to runtime errors.

The `bug.groovy` file shows a simple method that fails if either of its input parameters is null.  The `bugSolution.groovy` shows how to solve this problem using Groovy's safe navigation operator.

This demonstrates the importance of defensive programming in Groovy, particularly when dealing with external data or user input where null values are a possibility.