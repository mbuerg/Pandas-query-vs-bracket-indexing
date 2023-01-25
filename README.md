# Pandas-query-vs-bracket-indexing
This projects looks at time needed to conditionally index a Pandas dataframe via df.query and via df[] brackets with two conditions.

It is found that bracket performs better up to a million rows.
Furthermore the difference in computation time gets bigger and bigger. However the quotient stabilizes around 5% to 6%. That is for big dataframes df.query needs 5 to 6 percent longer.

![query_vs_bracket_1](https://user-images.githubusercontent.com/106337257/214600999-8f408251-d1c3-42de-883d-08d96385df49.png)

![query_vs_bracket_2](https://user-images.githubusercontent.com/106337257/214601032-038a4385-9c4b-4b30-9393-2f965aa72b78.png)

![query_vs_bracket_3](https://user-images.githubusercontent.com/106337257/214593300-ff4276e2-e410-48aa-aec0-54b7af34a7fb.png)

Test was run on datacamp free workspace.

To Do:
1. More simulations such as different conditions for indexing and different dtypes in the data frame
2. More sophisticated statistical analysis if needed
