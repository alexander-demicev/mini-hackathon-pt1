# Statistics
## Complexity 44%

Vasya does not like English, but he tries to get at least 4. In the current semester, Vasya noticed the following pattern: on odd days of the month he received 3, and on even days - 4. He also remembers on which days he received these marks. Therefore, he wrote out on paper all these days in order to calculate how many 3 he has and how many 4 he has. Help Vasya do this by arranging even and odd numbers in different lines. Vasya can count on getting mark 4 if the is not less than 3 than 4.

INPUT contains N numbers representing the given array. Each element of the array is a natural number from 1 to 31.

OUTPUT the numbers that correspond to the days of the months in which Vasya received triples, respectively, arrange the dates of the month in which Vasya received 4. Then, output “YES”, if Vasya can count on 4, and “NO” otherwise. In each line of the number should be displayed in the same order in which they go in the input data.

| INPUT                             | OUTPUT                           |
|-----------------------------------|----------------------------------|
| 4 16 19 31 2	                    | [[19 31], [4 16 2], 'YES']       |
| 29 4 7 12 15 17 24 1	            | [[29 7 15 17 1], [4 12 24], 'NO']|
