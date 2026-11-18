# Run on Fossil Fuels
Replication code for the JFE Paper "A Run on Fossil Fuel? Climate Change and Transition Risk" by Michael Barnett.

To derive the results in the paper, there are two main sets of code that need to be run:
1. Motivating Empirical Analysis (Section 3 of the paper)
2. Numerical Solutions of the Dynamic Model of Climate-Linked Transition Risk (Sections 4-6 of the paper)
   
This repository contains folders for each set of results. I outline the code provided, as well as details about running the code, in order to allow users to replicate the results provided in the paper.

## Section 3: Motivating Empirical Analysis
Results for the empirical analysis require the following code and data:
1. ...
2. ...
3. ...

## Sections 4 - 6: Numerical Solutions of the Dynamic Model of Climate-Linked Transition Risk
There are multiple model specifications solved to derive the numerical results from the model:
1. ... (Baseline model competitive equilibrium)
2. ... (Baseline model social planner's solution)
3. ... (Alternative model specifications)

## Appendix Material
There are a number of additional results in the appendix...
1. ...
2. ...

## Replicating the Results

In order to replicate the results, you will need to run each of these codes for each of the cases specified in the paper. There are ... empirical specifications, ... baseline model cases, and ... alternative model specifications. 

The code in each set needs to be run in the order listed above, where the "SmartCases" codes are only needed if you'd like to derive solutions with alternative parameter values using existing solutions as initial guesses for the value function.

I ran the empirical jobs using Stata 18 on my personal laptop. Each model solution case takes ... hours to run.

I ran the theoretical jobs on the ASU Sol high-performance-computing servers. This was done to run multiple jobs simultaneously. This can also be done reasonably using Matlab on a personal laptop. Each model solution case takes ... hours to run.
