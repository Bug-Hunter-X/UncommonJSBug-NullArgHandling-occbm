# Uncommon JavaScript Bug: Null Argument Handling

This repository demonstrates a common yet easily overlooked error in JavaScript: improper handling of null or undefined function arguments.  The `bug.js` file showcases the problematic code, while `bugSolution.js` provides the corrected version.

The bug arises when a function doesn't explicitly check for null or undefined arguments.  This can lead to unexpected behavior, such as `TypeError` exceptions or incorrect results.

The solution emphasizes the importance of adding explicit null checks at the beginning of your functions. This makes your code more robust and easier to maintain.

## How to Run

1. Clone the repository.
2. Open the `bug.js` and `bugSolution.js` files in your preferred code editor or IDE.
3. Observe the differences in the code and how the explicit null checks prevent unexpected errors.