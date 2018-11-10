# Secret message
## Complexity 36%

Encryption arrived on a secret base in the Arctic - a sequence of n decimal digits. It contains the number of secret base in Antarctica, which is a sequence of k decimal digits. At the same time, to distinguish this number from the information you do not need, it is repeated at least twice in encryption (these two occurrences can overlap).

Write a program that, by encryption and the length of the secret base number, determines if the encryption contains the base number. Note that the base may have several numbers, and all of them can be transferred in encryption.

INPUT The first line of the input file contains two integers: n (1 ≤ n ≤ 105) and k (1 ≤ k ≤ 5) - the length of the encryption and the length of the secret base number, respectively. The second line contains n digits - encryption. Remember that the numbers in the encryption are not separated by spaces.

OUTPUT In the output file output &quot;YES&quot; if the encryption contains the secret base number, and &quot;NO&quot; otherwise.


| INPUT                 | OUTPUT                 |
|-----------------------|------------------------|
| 10 5<br>0123456789    | NO                     |
| 13 2<br>0123400056789 | YES                    |
