# Let's look at the ROUND function:

- ROUND(value): rounds the number you give as input, value.
- For example, a cell that contains =ROUND(7.27) would evaluate to 7:

# Function composition - SQRT

- to use the output of one function as input to another function. Google Sheets will first evaluate the innermost function, 
   and use the result as an argument for the outer function. Combining functions like this is called function composition.

- SQRT(value): the square root of a value

# Functions and ranges - MIN, MAX

-MIN and MAX. Arguments can be ranges, where every value in the range is checked (e.g. =MAX(A1:A7)):
```
MIN(value1, [value2, ...]): searches for the minimum value in its arguments
MAX(value1, [value2, ...]): searches for the maximum value in its arguments
```
# Selecting ranges - SUM, AVERAGE, MEDIAN
```
each can have ranges as arguments:

SUM(value1, [value2, ...]): calculates the sum of all its arguments
AVERAGE(value1, [value2, ...]): calculates the average of all its arguments
MEDIAN(value1, [value2, ...]): calculates the median of all its arguments

```
# Multiple arguments - RANK

- RANK gives you an idea how a value compares to other values in a range. For example, in our example, it can be used to find out which were the top 5 months in terms of revenue. Specifically:

- RANK(value, data): evaluates to the rank of value in a range, data

- an absolute reference in C2: =RANK(B2, $B$2:$B$13).
