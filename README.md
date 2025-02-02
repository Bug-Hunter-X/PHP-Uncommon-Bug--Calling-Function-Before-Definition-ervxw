# PHP Uncommon Bug: Calling Function Before Definition

This repository demonstrates a common, yet subtle, error in PHP: calling a function before it has been defined.  This can lead to unexpected behavior and runtime errors if not carefully addressed.

## Bug Description
The `bug.php` file showcases the problem.  The `myFunction()` is called before its declaration, resulting in an error if strict error reporting is enabled. 

## Solution
The solution, in `bugSolution.php`, ensures that the function definition precedes all calls to the function.