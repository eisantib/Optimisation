# Code created by Ernesto Santibanez
# Optimisation

This repository contains optimisation related codes

1) Pareto front quality parameters calculation

This code calculates quality parameters for multi objective optimization obtained optimal solutions.
Obtaining the Pareto optimal front in Multi objective optimization problems can be computationally demanding, which is why many meta-heuristic methods are popular. Some methods might produce 'better' Pareto front approximations than other; being able to analyze and compare between different Pareto front approximations is relevant at the moment of deciding which algorythm gives better results than other, or to estimate how dense/stable/different the obtained optimal solutions are.

This code estimate Pareto front quality indicators using Python 3. The obtained optimal solutions are assumed to be imported in .csv format.
