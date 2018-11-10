# Five five - twenty five!
## Complexity 8%

Vasya and Petya study in the same class at school. Recently, Petya told Vasya about a clever method of squaring natural numbers with digit 5 at the end. Now Vasya can easily square two-digit (and even some three-digit) numbers ending with 5. The method is as follows: for squaring a number, ending with 5, it is enough to multiply the number obtained from the original one by removing the last digit, by the next number in order, then all that remains is to add “25” to the right part of result. For example, to find number 125 square, it is enough to multiply 12 by 13 and add 25, i.e. append to number 12 * 13 = 156 number 25, we get the result 15625, i.e. 125^2 = 15625. Write the program, that calculate square of number ending with 5, so that Vasya could test his skills.

INPUT contains one positive integer A, ending in a number 5, not exceeding 4 * 105.

OUTPUT output one positive integer - A^2 without leading zeros.
