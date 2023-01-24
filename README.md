# Pandas-query-vs-bracket-indexing
This projects looks at time needed to conditionally index a Pandas dataframe via query and via brackets with two conditions.

It is found that bracket perform better up to a million rows.
Furthermore the difference in computation time gets bigger and bigger.

![query_vs_bracket_1](https://user-images.githubusercontent.com/106337257/214431156-c40b741f-1ec1-49ed-bc8a-cd54d63af5f7.png)

Test was run on datacamp free workspace.

To Do:
1. More simulations such as different conditions for indexing and different dtypes in the data frame
2. More sophisticated statistical analysis if needed
