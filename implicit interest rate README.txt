Here is my project in which I have created a code that determines
the implicit interest rate given the following information:
- Present value -> the amount of money I would pay in a 1 payment structure
- C -> amount of money to be paid monthly
- n -> number of payments

example:
Present value = 100.000
To be paid per month = 10.000
Number of months = 12

In this example, I have to choose between a single payment of 100.000
or 12 payments of 10.000 each for 12 months.
The implicit interest rate of the second option is calculated by the 
defined function implicit_interest(), which returns the value of 2.92%
