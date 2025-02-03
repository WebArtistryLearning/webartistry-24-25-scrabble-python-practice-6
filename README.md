# Scrabble

## Instructions

In the game of Scrabble, players create words to score points, and the number of points is the sum of the point values of each letter in the word.

| A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q  | R | S | T | U | V | W | X | Y | Z  |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|----|---|---|---|---|---|---|---|---|----|
| 1 | 3 | 3 | 2 | 1 | 4 | 2 | 4 | 1 | 8 | 5 | 1 | 3 | 1 | 1 | 3 | 10 | 1 | 1 | 1 | 1 | 4 | 4 | 8 | 4 | 10 |

For example, if we wanted to score the word “CODE”, we would note that the ‘C’ is worth 3 points, the ‘O’ is worth 1 point, the ‘D’ is worth 2 points, and the ‘E’ is worth 1 point. Summing these, we get that “CODE” is worth 7 points.

In a file called `scrabble.py`, implement a program in Python that determines the number of scores that a given word results in. For example, when the user enters `CODE`, the program should output `7`. The cases of the letters don't matter.

## Sample Checkpoints

### Sample Checkpoint 1

**Sample Input**

```
CODE
```

**Sample Output**

```
7
```

**Comment**

C + O + D + E = 3 + 1 + 2 + 1 = 7.

### Sample Checkpoint 2

**Sample Input**

```
rEd
```

**Sample Output**

```
4
```

**Comment**

r + E + d = 1 + 1 + 2 = 4.
