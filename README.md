# Titanic
Get started with kaggle problems using statistical and ML techniques

1. Start data exploration with pivots and data visualizations.
2. Add results from logistic regression. Ignoring large p-values since the plan is to use bayesian hierarchical logistic regression with weakly informative regularizing priors. Regularizing prior takes care of the parameters with large p-values in logistic regression.
3. Code up stan model in C++ and execute parallel chains on a multi-core system
4. Check convergence metrics (R_hat and traceplots) and posterior distribution
5. Compute posterior predictive in the form of MAP since the goal is to genrate point estimate for each passenger

Next steps:
1. Observed large standard deviation in prior grouping. Re-evaluate prior grouping.
