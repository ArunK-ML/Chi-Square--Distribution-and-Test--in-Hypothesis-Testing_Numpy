# Chi-Square-Test-in-Hypothesis-Testing_Numpy
seminar

The Chi-Square (χ²) test is a non-parametric statistical test used to determine whether:

==> Two categorical variables are related (Test of Independence), or
==> An observed distribution fits an expected distribution (Goodness of Fit Test).

 Types of Chi-Square Tests:
 
1. Chi-Square Test of Independence
Tests whether two categorical variables are independent.

Example: Is gender related to product preference?

2. Chi-Square Goodness of Fit Test
Tests whether a single categorical variable follows a specific distribution.

Example: Does a dice show equal probability for all sides?

| Concept            | Chi-Square Goodness of Fit | Chi-Square Independence                                                  |
| ------------------ | -------------------------- | ------------------------------------------------------------------------ |
| Use Case           | One categorical variable   | Two categorical variables                                                |
| Input              | One row of observed values | Contingency table                                                        |
| Test Formula       | $\sum \frac{(O-E)^2}{E}$   | $\sum \frac{(O-E)^2}{E}$                                                 |
| Degrees of Freedom | n - 1                      | (rows - 1)(columns - 1)                                                  |
| Concept            | Chi-Square Goodness of Fit | Chi-Square Independence      
| Lib Function       | chisquare                  | chi2_contingency 
| ------------------ | -------------------------- | ------------------------------------------------------------------------ |
                             

