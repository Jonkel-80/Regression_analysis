# Regression analysis
We discuss the python codes for running a simpl linear regression for scattered plots.
- The following methods were applied:
### The Least Squares Method Equation
$$ slope = \frac {n\sum_{i=1}^n (x_i y_i) - \sum_{i=1}^n x_i \sum_{i=1}^n y_i} {n\sum_{i=1}^n (x^2)-\sum_{i=1}^n(x)^2} $$

$$ Intercept = \frac {\sum_{i=1}^n y_i - m \sum_{i=1}^n y_i} {n} $$

### Deviation method

$$ slope = \frac {\sum_{i=1}^n (x_i - x_{mean})(y_i-y_{mean})} {\sum_{i=1}^n (x_i - x_{mean})(x_i - x_{mean})} $$

#### Where:
- $x_i$  = Values of x 
- $x_{mean}$ = Mean value of x values 
- $y_i$ = Values of y 
- $y_{mean}$ = Mean value of y values
- $m$ = slope
- $n$ = Number of observation points
  
Both methods were used to calculate the slope and intercepted. These gave the same results.
