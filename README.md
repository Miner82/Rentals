# Rentals
A look at price-demand sensitivity for apartment leases
An analytics firm has been asked by a leasing company
to look at the price-demand sensitivity of apartment rents.
More specifically, can revenue (rents) be better optimized. it is known that rents can be demand sensitive (as the stock of unleased units goes down, the rent quoted can go up.
We are given about five years of leasing history (2012-2018), rent rates, leases, and 11 types of apartment plans - studio with loft, 2 BR, 1BR etc.
I had a difficult time coding a boolian 'occupied' or 'unoccupied' in R based solely on a Start and End date.    As a first try, I recoded the Julian start and end dates ("01/01/2017") into time numeric periods (2017.01) and used Starts as a surrogate for demand.    See charts below for Lease Starts vs. Rent Rates for a sample floor plan below.
Not certain how to proceed with expanding the Start and End into occupied time periods, I chose one year, and rebuilt the original data set into numeric 1 or 0 for each month of the lease, per unit plan type.   With this, i hope to look at the percent occupied (leased) vs. rent rates.   From the dataset, each of the 11 floor plans has 100 units in inventory.
