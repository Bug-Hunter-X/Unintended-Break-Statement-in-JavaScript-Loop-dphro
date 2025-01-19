# Unintended Break Statement in JavaScript Loop

This repository demonstrates a common error in JavaScript: the unintended use of the break statement in a loop.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

The bug arises from a misplaced or incorrectly used `break` statement within a loop. This can lead to unexpected loop termination and incorrect program behavior.  Understanding the proper use of break statements, and careful code review, is crucial to avoid this type of error.

**How to reproduce:**
1. Clone this repository.
2. Run `bug.js` using a JavaScript interpreter (like Node.js).
3. Observe that the loop terminates prematurely at `i = 5`.  This is the unintended behavior caused by the break statement.
4. Run `bugSolution.js`. This shows the corrected logic where the loop runs to completion.

This example highlights the importance of careful code design and thorough testing to prevent logic errors related to loop control statements.