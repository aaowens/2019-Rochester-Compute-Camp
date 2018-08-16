# Homework
## Exercise 1:
In this exercise you will plot a graph showing how optimal hours worked changes with the wage rate. This is in reference to the first optimization problem in the utility script. 

First, set assets = 1 so that the income and substitution effects stop canceling out.

Construct a grid (a vector) of wages from 1 to 3, spaced by 0.05. Your goal is to construct a vector of h^star(w), the optimal hours at that level of wages. Finally, construct a plot where the x-axis is the wage grid and the y-axis is h^star. You will need to use a for loop to iterate over each point on the wage grid, and solve the optimization problem at each point.

## Exercise 2:
In the econometrics simulation code, modify the measurement example so that the error is in y instead of in x_2. Specifically, we do not observe y, but we observe y + noise. Compute the OLS estimates of the betas in this case and report how the estimates are or are not different from the true values.
