# TypeScript Loop Early Exit Bug

This repository demonstrates a subtle bug in TypeScript where a `return` statement inside a `for` loop can lead to unexpected early termination of the loop before all iterations are complete.

## Bug Description
The `printNumbers2` function is intended to print numbers from 1 to n. However, due to the `return` statement when `i` equals 3, the loop terminates prematurely.  This is counter-intuitive if you're not paying close attention to the placement of the return statement.

## How to Reproduce
1. Clone this repository.
2. Compile and run the TypeScript file.