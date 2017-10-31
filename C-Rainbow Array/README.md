# Problem C (Rainbow :rainbow: Array)
:page_facing_up: **Input file name** : C.txt

## :green_book: Problem description ##
An array is Rainbow :rainbow: if it contains the **7 known colors** (from 1 to 7) and **has the following structure**:
- First `a1` elements equal 1.
- Next `a2` elements equal 2.
- Next `a3` elements equal 3.
- Next `a4` elements equal 4.
- Next `a5` elements equal 5.
- Next `a6` elements equal 6.
- Next `a7` elements equal 7.
- Next `a6` elements equal 6.
- Next `a5` elements equal 5.
- Next `a4` elements equal 4.
- Next `a3` elements equal 3.
- Next `a2` elements equal 2.
- Last `a1` elements equal 1.

We want to verifiy for each array from input file if it is Rainbow.

## Input ##
- The first line of the input contains an integer T denoting the number of test cases.
- The first line of each test case contains an integer N, denoting the number of elements in the given array.
- The second line of a test case contains N space-separated integers A1, A2, ..., AN denoting the elements of array.

## Output ##
- For each test case, output a line containing `yes` or `no` corresponding to the case if the array is rainbow array or not.

## Constraints ##
- **1 ≤ T ≤ 10**
- **7 ≤ N ≤ 30**

### Example ###
**Input** (C.txt)
```
3
19
1 2 3 4 4 5 6 6 6 7 6 6 6 5 4 4 3 2 1
14
1 2 3 4 5 6 7 6 5 4 3 2 1 1
13
1 2 3 4 5 6 8 6 5 4 3 2 1
```

**Output**
```
yes
no
no
```

## :no_entry: Notice ##
1. You should **never make control on input data**. When presenting a problem, all **input data is supposed to be valid**. 
2. The constraints are especially useful for variables allocations. For example: choosing the **maximum size of declared array** variable or 
choosing the right numerical types to use (`int` vs `short` vs `float`) ; refer to "**[C Cheat Sheet Reference Card](https://www.math.brown.edu/~jhs/ReferenceCards/CRefCard.v2.2.pdf)**", section "**Types Limits**".
