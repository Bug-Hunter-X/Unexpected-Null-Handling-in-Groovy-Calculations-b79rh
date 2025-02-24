# Groovy Null Handling Bug

This example demonstrates a potential issue with null handling in Groovy calculations.  Groovy's dynamic typing can lead to unexpected behavior if null values are not explicitly handled. The `calculate` function provides a basic solution, but more sophisticated checks may be necessary in larger applications.

## Bug Description

The `calculate` function does not always behave as expected when one or both inputs are null.  The solution shows a more robust method of handling null values.  See the GroovyNullHandlingBug.groovy and GroovyNullHandlingSolution.groovy files for code examples. 