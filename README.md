# Optimization-With-R
Simple demonstration of how to optimize with R. 

Here is the case: You are a portfolio manager who wishes to maximize bond returns, given restraints pertaining to:
1. Maximum allocations to a given security 
2. Maximum allocations to a given sector
3. Total portfolio duration limit

Given a matrix of securities with class, yield, and duration, this script specifies thresholds and then determines allocations to the set of securities that maximize total return under the stated constraints
