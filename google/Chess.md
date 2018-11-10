# Chess
## Complexity 23%

Recently, Vasya started programming and decided to implement his own program for playing chess. But he had the problem of determining the correctness of the knight’s move, which the user makes. If the user enters the value &quot;C7-D5&quot;, then the program should define it as the correct move, if entered &quot;E2-E4&quot;, then the move is incorrect. It is also necessary to check the correctness of the entered record: if, for example, “D9-N5” is entered, then the program should define this entry as erroneous. Help him make this check!

INPUT contains the text of the move (non-empty line) that the user specified. The user cannot enter a string longer than 5 characters.

OUTPUT, you need to output “YES”, if the indicated move is the knight, the correct one, if the record is correct (in the sense of correctness of the coordinates), but the move is impossible, then “NO” should be output. If the coordinates are not defined or specified incorrectly, then display the message “ERROR”.
