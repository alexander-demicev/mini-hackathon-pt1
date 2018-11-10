# Clock
## Complexity 30%

Petya loves to observe electronic watches. He was looking at his watch all day long and counted how many times each digit occurs. After a few months, he learned how to say for any period of time, how many times on the clock during that time each digit would occur, and he was very proud of it.

Vasya decided to check Petya's skill, but he does not know how to do it. Vasya asked you to help him. Write a program that solves this problem.

The first and second lines of the input file INPUT.TXT contain the beginning and end of the time interval, respectively. The initial time does not exceed the final one. The time is specified in the format hh: mm: ss (0 ≤ hh &lt;24, 0 ≤ mm &lt;60, 0 ≤ ss &lt;60). hh, mm, ss are supplemented with leading zeros up to two characters. These zeros are also taken into account when counting the number of digits.
<br/>
The output OUTPUT.TXT file must contain 10 lines. The i-th line should contain the number of times i-1 occurs.


| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 1 3	                              | 1                      |
| 2 7	                              | 21                     |
| 3 10	                            | 274                    |
