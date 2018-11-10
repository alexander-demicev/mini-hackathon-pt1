# Bunny
## Complexity 55%

A bunny appeared in our zoo :). He was placed in a cage, and so that he was not bored, the manager of the zoo asked to put a ladder in his cage. Now our bunny can jump up the ladder, jumping over the steps. A ladder has a certain number of steps N. A bunny can jump over no more than K steps in one leap. For a fun, the bunny is trying every time to find a new path to the top of the stairs. The manager is curious how many different ways the rabbit has to get to the top of the stairs for given values ​​of K and N. Help the manager to write a program that will help to calculate this number. For example, if K = 3 and N = 4, then there are the following routes: 1 + 1 + 1 + 1, 1 + 1 + 2, 1 + 2 + 1, 2 + 1 + 1, 2 + 2, 1 + 3, 3 + 1. Thus with this input, the bunny has only 7 different routes to the top of the stairs.

![Bunny](https://acmp.ru/asp/article/image.asp?id=146)

INPUT contains two natural numbers K and N (1 ≤ K ≤ N ≤ 300). K is the maximum number of steps that the bunny can overcome in one jump, N is the total number of stairs.

OUTPUT number of possible options for different bunny routes to the top of the ladder without leading zeros.

| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| 1 3	                              | 1                      |
| 2 7	                              | 21                     |
| 3 10	                            | 274                    |
