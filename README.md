# Titanic
Get started with kaggle problems using statistical and ML techniques

Started data exploration with pivots and data visualizations.
Added results from logistic regression. Ignoring large p-values since the plan is to use bayesian hierarchical logistic regression with weakly informative regularizing priors. The regularizing prior takes care of the parameters with large p-values in logistic regression.

Next steps:
1. Code up stan model in C++ and execute parallel chains on a multi-core system
2. Check R_hat and visualize traceplots and posterior distribution to evaluate convergence of posterior
3. Compute posterior predictive in the form of MAP since the goal is to genrate point estimate for each passenger
