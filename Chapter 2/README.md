# Survival_Analysis_Varying_Mixing_Weights
Survival Analysis with Varying Mixing Weights as part of a CIFRE thesis in Applied Mathematics 


In the article "Measuring information loss when modeling sick leave with weight mixture models", we consider a problem in actuarial sciences, in which we have M insurance companies (samples) and K groups of insured persons. We want to model sick leave for each group. However, the group label of each observation is not defined with certainty for confidential reasons. We assume that each insurance company can provide the proportion of each group in its database. In this case, we are going to compare two different Kaplan-Meier estimators for mixture models. We measure the information loss when modeling sick leaves with variable weight mixture models in censored duration models, comparing Ryzhov's and Maiboroda's methods, both using simulations and empirical data. 

Here are the codes used for the simulations for differents kind of function : exponnential law, Pareto's law, Weibull's law, Gamma's law. 

1 - Contextualization
 - Ryzhov Method
 - Maiboroda Method
   
2 - Libraries import

3 - Optimized functions
 - Survival functions
 - Simulation functions
 - Kaplan-Meier function of Maiboroda
   
4 - Simulations
 - Parameters choice
 - Inverted weight matrix
 - Simulation of observations
 - Ryzhov's method
 - Maiboroda's method
 - Results comparison
   
5 - Simulation automation
 - Additional functions
 - Simulation parameters
 - Simulations

You can contact the author at margaux.thorez@centrale-marseille.fr
