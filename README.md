# Practice: Change Maker

In this practice, you will implement a change calculator. Your program should prompt the user for the amount of money due, and the amount of money paid.

The program should then calculate the change due and output how much of each bill/coin (from a twenty-dollar bill to pennies) are needed. The goal should be to output the least number of coins and bills.

## Input
1. The amount due
2. The amount paid

## Output
The change due formatted in the style: $x.xx
The number of coins/bills needed: pennies, nickels, dimes, quarters, and one, five, ten, twenty-dollar bills.

Print the error messages for the following cases.
- The amount due is $0.00 or less: "The amount due must be greater than $0.00."
- The paid is $0.00 or less: "The amount paid must be greater than $0.00."
- The amount paid is less than the amount due: "The amount paid must be greater than the amount due."

## Examples:

```
Inputs
0.50
1.00

Outputs
Change: $0.50
Twenty-dollar bills: 0
Ten-dollar bills: 0
Five-dollar bills: 0
One-dollar bills: 0
Quarters: 2
Dimes: 0
Nickels: 0
Pennies: 0
```

```
Inputs
1.36
5.00

Outputs
Change: $3.64
Twenty-dollar bills: 0
Ten-dollar bills: 0
Five-dollar bills: 0
One-dollar bills: 3
Quarters: 2
Dimes: 1
Nickels: 0
Pennies: 4
```

```
Inputs
3.13
20.00

Outputs
Change: $16.87
Twenty-dollar bills: 0
Ten-dollar bills: 1
Five-dollar bills: 1
One-dollar bills: 1
Quarters: 3
Dimes: 1
Nickels: 0
Pennies: 2
```

```
Inputs
13.59
50.00

Outputs
Change: $36.41
Twenty-dollar bills: 1
Ten-dollar bills: 1
Five-dollar bills: 1
One-dollar bills: 1
Quarters: 1
Dimes: 1
Nickels: 1
Pennies: 1
```

```
Inputs
-0.90
1

Outputs
The amount due must be greater than $0.00.
```

```
Inputs
5.31
0

Outputs
The amount paid must be greater than $0.00.
```

```
Inputs
2.03
1.00

Outputs
The amount paid must be greater than the amount due.
```