# Arithmetic

Last year, Joe went to school and learned to read. This year he learned the multiplication table and now knows how to multiply any numbers from 1 to 10 without errors. Friend Peter told him about number systems other than decimal. In particular, binary, octal and hexadecimal even. Now Joe can easily (but already using leaf and handles) can multiply the numbers from 1 to 10 and in these systems, using the translation from a non-standard system to decimal and vice versa from decimal. For example, if you want to multiply the number 101 Vaasa and 1001 in binary, it first converts these numbers in decimal notation as follows:
(101) 2 = 1 * 22 +0 * 21 +1 * 20 = 4 +0 = 5 +1
(1001) 2 = 1 * 23 +0 * 22 +0 * 21 +1 * 20 = 8 +0 = 9 +1 +0

Then multiplies the numbers 5 and 9 Vasya easily produces in decimal notation in mind and gets the number 45. Then the translation from decimal notation to binary. To do this, it divides a number 45 on Joe 2 (order number system), remembering the remnants of the Division, until as a result does not remain the number 0:

The answer is composed of residues obtained from dividing by recording them in reverse order. So Joe gets the result: (101) 2 * (1001) 2 = (101101) 2. But now Joe is studying multiplication table of numbers from 1 to 100 in decimal notation, and because remember such a table is very difficult, you have to have a really long its Vaasa cramming. Compose for Wasi program, which will help him to validate their knowledge.

In the input file INPUT. TXT recorded three natural numbers A, B, and C through the gap. A and B ≤ C ≤ 102 and 106.

In the output file you want to display YES if A * B = C and display NO otherwise.
