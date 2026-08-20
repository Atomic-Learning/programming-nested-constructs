# What Nested Constructs Are

When writing code, constructs such as conditionals and loops may be nested inside each other. This allows for more complex control flow and logic. For example, the code below will process each item in a list only if it meets certain criteria:

```
FOR each item IN list:
    IF item > 0:
        process(item)
```

In this example, the `IF` statement is nested inside the `FOR` loop. The loop iterates over each item in the list, and for each item, the conditional checks if it is greater than 0 and, if it is, processes it.

# Indentation

Indentation is commonly used to indicate which lines of code belong to which constructs. In the example above, the line `IF item > 0:` is indented one step to show that it belongs to the body of the `FOR` loop and will be executed for each item. The line `process(item)` is indented further to show that it belongs to the body of the `IF` statement and will only be executed if the condition is true.

In some languages, indentation of this sort is required for syntactic correctness, while in others it is purely for readability and clarity.
