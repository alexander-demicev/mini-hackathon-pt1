# Bulls and cows
## Complexity 26%

Petya and Vasya often play various logical games. Recently, Petya told Vasya about the new game &quot;Bulls and Cows&quot; and now they play this game all day long. The essence of the game is very simple: Petya thinks of a four-digit number that includes a various numbers. Vasya guesses the number that Petya think about, turning over possible options. Each time Vasya proposes a variant of his number, and Petya gives Vasya a hint: informs the number of bulls and cows, after which Vasya continues to guess the number, taking into account the hint, until he guesses. Bulls is the number of digits in the number proposed by Vasya, coinciding in value and standing in the correct position in the conceived number. Cows - the number of digits that match in value, but are in the wrong position. For example, if Petya conceived the number 5671, and Vasya proposed the variant 7251, then the number of bulls is 1 (only 1 is in its right place), and the number of cows is 2 (only numbers 7 and 5 are not in their places). Petya is good at math, but even he can be wrong. Help Petya to write a program that, according to the numbers conceived by Petya and proposed by Vasya, reported the number of bulls and cows.

INPUT Contains two four-digit positive integers A and B separated by a space, where A is the number that Petya made up and B is the variant proposed by Vasya.

OUTPUT Need to output two integers separated by a space - the number of bulls and cows.

| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 5671 7251	                        | 1 2                    |
| 1234 1234	                        | 4 0                    |
| 2034 6234	                        | 2 1                    |

