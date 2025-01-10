# Haskell Pattern Match Failure: Handling Empty Lists

This repository demonstrates a common Haskell error: a pattern match failure when using the `head` function on an empty list. The `head` function is only defined for lists with at least one element. Attempting to use it on an empty list will cause a runtime error.

The `bug.hs` file contains the erroneous code. The `bugSolution.hs` file provides a corrected version, demonstrating how to handle potential empty lists gracefully. 