This C++ code solves a problem likely from a competitive programming context. The `main` function handles multiple test cases. For each test case, it reads an integer `n`.

The core logic is to construct a permutation of numbers from 1 to `n`. If `n` is 4 or less, the code outputs -1, indicating no such permutation is possible or required by the problem.

For `n > 4`, the code generates a specific permutation:
1. It prints all even numbers from 2 to `n`, skipping 4.
2. It then prints 4 and 5.
3. Finally, it prints all odd numbers from 1 to `n`, skipping 5.

The output for each test case is this generated permutation or -1, followed by a newline.

This specific arrangement of numbers is likely designed to satisfy certain conditions of the problem it originates from (indicated by the Codeforces URL). The pattern aims to interleave even and odd numbers with special placement for 4 and 5.