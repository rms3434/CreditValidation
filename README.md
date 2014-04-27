CreditValidation
================
Check if a credit card number is valid. Guidelines...

Credit card numbers follow certain
patterns: It must have between 13 and 16 digits, and the number must start with:
■ 4 for Visa cards
■ 5 for MasterCard credit cards
■ 37 for American Express card
■ 6 for Discover cards

1. Double every second digit from right to left. If doubling of a digit results in a
two-digit number, add up the two digits to get a single-digit number.
4388576018402626
2 * 2 = 4
2 * 2 = 4
4 * 2 = 8
1 * 2 = 2
6 * 2 = 12 (1 + 2 = 3)
5 * 2 = 10 (1 + 0 = 1)
8 * 2 = 16 (1 + 6 = 7)
4 * 2 = 8
2. Now add all single-digit numbers from Step 1.
3. Add all digits in the odd places from right to left in the card number.
4. Sum the results from Steps 2 and 3.
5. If the result from Step 4 is divisible by 10, the card number is valid; otherwise,
it is invalid. For example, the number 4388576018402626 is invalid, but the
number 4388576018410707 is valid.

Starting functions to come. To be done in Python 3
