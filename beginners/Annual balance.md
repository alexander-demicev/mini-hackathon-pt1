# Annual balance
## Complexity 35%

The "Blue Hat" company is calculating the annual balance. The accounting department received information that, according to the documents, the total expenses are A crowns, and the total income - B crowns. Since these numbers still have nothing to do with the real state of affairs, the accountant decided to implement his next idea. As you know, when typing numbers on a computer, people often enter numbers in the wrong order. Therefore, the accountant wants to find such a way to rearrange the digits in the numbers A and B, in a way that as a result the difference between A and B (the amount of money he puts in his pocket) is maximum, and in any case you can refer to the secretary’s mistake. We must not forget about the sign of numbers and that zero cannot be the first digit of a number other than zero. Write a program that will help the accountant.

INPUT contains two integers a and b (-109 < a, b < 109).

OUTPUT print a single integer - the largest difference of numbers, the first one can be obtained by rearranging the digits A, and the second - by rearranging the digits B.

| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 18 10                             | 71                     |
| 1 -23                             | 33                     |
