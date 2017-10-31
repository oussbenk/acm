# Problem B (Say Hello folks)
:page_facing_up: **Input file name** : B.txt

## :green_book: Problem description ##
We want to say hello to many people. The names are read from an input text file which contains in the first line 
the number of persons to welcome. Each name is written in a separate line.

The names should be all printed in capital (upper) case and each message must be numbered. Welcome messages must also alternate 
between "Hello" and "Hi" (see the example below).

### Example ###
**Input** (B.txt)
```
4
Alice
bob
carOL
DaVe
```

**Output**
```
1. Hello ALICE!
2. Hi BOB!
3. Hello CAROL!
4. Hi DAVE!
```

## :sos: Hints ##
1. Obviously, names should be processed with a loop. The number of iterations (called also "Test Cases") is specified in the input first line.
2. To alternate between messages, test if iteration is even or odd (use the `%` modulo operator in C).
3. Use string and character functions to convert letters from lower to upper case. You should also include the required libraries 
(refer to the "**[C Cheat Sheet Reference Card](https://www.math.brown.edu/~jhs/ReferenceCards/CRefCard.v2.2.pdf)**").
