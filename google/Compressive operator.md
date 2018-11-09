# Compressive operator

Operator A, acting from the set X to the set Y (or simply the operator from X to Y) is the rule according to which each element x of the set X is associated with an element y = Ax from the set Y. Let X and Y be the sets of points on the plane. An operator A from X to Y is called contractive with the coefficient q, where q is a real number from the half-interval [0, 1) if for any x from X we have || Ax || ≤ q * || x || (here || x || - the norm of the point x - the distance from x to the origin). In simpler terms, an operator is called contractive with a coefficient q if it associates with each point a point that is not less than q times closer to the origin.

For a given operator A, it is necessary to check whether it is contractive with the coefficient q.

The first line of the input file INPUT.TXT contains the number of points n (1 ≤ n ≤ 100) and the number q (0 ≤ q &lt;1), specified with no more than 3 characters after the decimal point. The next n lines contain 4 integers each, not exceeding 1000 in absolute value, separated by spaces — the coordinates of the point of the set X and the point associated with it from the set Y.

In the output OUTPUT.TXT file, output one word: “Yes” if the operator is compressive with a factor q and “No” otherwise.
