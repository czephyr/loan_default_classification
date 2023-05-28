## loan_default_classification
The submission scored 1st on the [OpenDataPlayground challenge](https://opendataplayground.com/challenge/credimi-graduate-program-data-science) organized by the italian fintech company [Credimi](https://www.linkedin.com/company/credimi-s.p.a./) for data science students.

We were asked to predict if SMEs in the datasets would default on a loan using financial KPIs such as EBITDA, Net Financial Position, revenue etc.

The employed model was a LGBM with Bayesian hyperparameter Optimization over a Stratified Cross Validation required by the unbalanced nature of the dataset.
