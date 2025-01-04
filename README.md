# Julia Integer Overflow Bug

This repository demonstrates a subtle integer overflow bug in a simple Julia function. The function `myfunction` squares its input if the input is greater than 10; otherwise, it adds 1 to the input.  The problem arises when the input is a very large integer, causing potential integer overflow. 

The `bug.jl` file contains the buggy code.  The `bugSolution.jl` file provides a corrected version that addresses the overflow issue.  The solution involves using arbitrary-precision integers to handle potentially very large inputs.