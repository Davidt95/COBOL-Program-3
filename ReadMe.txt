This project is designed to take six loan parameters and generate a 
 customized loan amortization schedule for the borrower. To ensure 
 persistence of the program we designed it to take any number of 
 customers, and used an independently modifiable lookup table to generate 
 our loan types.

The success report showcases each monthly payment over the life of the
 loan as it splits between principal and interest and the resulting ending balance.

The program is also written to recognize errors in the input data and generates 
 an exception report specifying issues including:

	1. Missing/Non-Numeric APR
	2. Missing/Non-Numeric Term
	3. Missing/Non-Numeric Principal Amount
	4. Loan Type not found in Table

The output reports are formatted to be printed on a standard sheet of 55 lines with 132 characters 
 per line, with page and loan headers repeated at a new page or new loan.