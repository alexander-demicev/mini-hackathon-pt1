# Computer game
## Complexity 38%

Can you remember at least one of your friends that younger then 20 year old, who in childhood did not play computer games? If so, then maybe you are not familiar with this entertainment too? However, this should not create difficulties in solving this problem.

In many old games with two-dimensional graphics, you can face a similar situation. Any hero jumps on platforms (or islets) that hang in the air. He must move from one edge of the screen to the other. At the same time, when jumping from one platform to the next, the hero leaves | y2-y1 | energy units, where y1 and y2 are the heights on which these platforms are located. In addition, the hero has a super reception that allows you to jump across one platform, but it takes 3 * | y3-y1 | units of energy. Of course, energy should be used as economically as it possible.

Suppose that you know the coordinates of all the platforms in order from the left edge to the right. Can you find out what energy minimum the hero needs to get from the first platform to the last one?

INPUT contains the number of platforms n (1 ≤ n ≤ 30000). The second line contains n natural numbers not exceeding 30,000 — the heights on which the platforms are located.

OUTPUT file, write down a single number - the minimum amount of energy that the player must spend on overcoming the platforms (of course, assuming that cheat codes cannot be used).


| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 3     	                        | 9                      |
| 1 5 10                            |                        |
| 3     	                        | 3                      |
| 1 5 2		                        |                        |

