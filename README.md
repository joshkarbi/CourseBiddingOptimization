# Course-Bidding-Optimization
A linear programming model to optimize a bidding strategy for seats in classes.

# Dependencies
- PuLP linear programming library for Python

# Output
Outputs three files:
- conservative.out (Need to bid avg(historical)+1SD to get into a course)
- base.out (Can just bid avg(historical) to get into course)
- aggressive.out (Assuming you can bid avg(historical)-1SD and still get into course)