# Best divisor
## Complexity 26%

Assume that A is better than the number B if the sum of digits A is greater than the sum of digits of number B, and in case of equality of the sums of their digits if the number A is less than the number B. For example, the number 124 is better than the number 123, since the first one has the sum equal to 7, and the second 6. Also, the number 3 is better than the number 111, since they have the same sum of numbers, but the first number is smaller.

Given the number N. Find such a divisor of it (the number N and 1 are considered divisors of the number N), which is better than any other divisor of the number n.

INPUT contains an integer n (1 ≤ n ≤ 105).

Output the answer to the problem.

| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 10	                              | 5                      |
| 239	                              | 239                    |
