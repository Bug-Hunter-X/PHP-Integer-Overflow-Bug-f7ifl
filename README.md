# PHP Integer Overflow Bug

This repository demonstrates a common yet subtle bug in PHP: integer overflow.  When dealing with extremely large numbers, PHP's integer type can overflow, leading to unexpected results, often negative numbers.  This can cause significant issues in calculations and data handling.

The `bug.php` file contains the problematic code.  The `bugSolution.php` file provides a solution demonstrating how to mitigate the risk of integer overflow using the GMP library.