# Chi-Square-Test-in-Hypothesis-Testing_Numpy
# Chi-Square-Distribution-in-Hypothesis-Testing_Numpy
seminar

**Chi-Square Distribution in Hypothesis Testing (with NumPy)**

📘 1. What is the Chi-Square Distribution?
The Chi-Square (χ²) distribution is a continuous probability distribution used in:

----> Variance testing
----> Goodness-of-fit
----> Test of independence (categorical data)

It is positively skewed and depends on degrees of freedom (df).

🧪 2. When to Use the Chi-Square Test?
✅ Use the Chi-Square Test for Variance when:

You want to test if the sample variance is equal to a known population variance (σ²)

Data is normally distributed

**Chi-Square (χ²) test**

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

                             

| **Concept**            | **Chi-Square Goodness of Fit** | **Chi-Square Independence**   | **Chi-Square Variance Test**                         |
| ---------------------- | ------------------------------ | ----------------------------- | ---------------------------------------------------- |
| **Use Case**           | One categorical variable       | Two categorical variables     | Compare sample variance to known population variance |
| **Input**              | One row of observed values     | Contingency table             | Numerical data (normally distributed)                |
| **Test Formula**       | $\sum \frac{(O - E)^2}{E}$     | $\sum \frac{(O - E)^2}{E}$    | $\chi^2 = \frac{(n - 1) \cdot s^2}{\sigma^2}$        |
| **Degrees of Freedom** | $n - 1$                        | $(r - 1)(c - 1)$              | $n - 1$                                              |
| **Library Function**   | `chisquare`                    | `chi2_contingency`            | Manual formula using `scipy.stats.chi2.ppf()`        |
| **Data Type**          | Categorical                    | Categorical                   | Continuous (numerical)                               |
| **Goal**               | Test if data fits distribution | Test if variables are related | Test if variance equals claimed value                |
