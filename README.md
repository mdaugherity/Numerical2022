# PHYS 351: Applied Numerical Methods
## Fall 2022
Dr. Mike Daugherity, Abilene Christian University

This repository is for code and data files.  All other course information is posted on Canvas.

### Important Note 
Github's notebook renderer is trash.  Pages will often not display correctly. 
**One workaround is to view the pages on [nbviewer](https://nbviewer.jupyter.org/github/mdaugherity/Numerical2022/tree/main/)**.  
Another approach is to open the files directly from Colab.

# OUTLINE
## Introduction and Review
* [Colab Cheet Sheat](intro/Week_1_Intro_to_Colab.ipynb) - A quick intro to python in Google Colab
* [Arrays and Plots](intro/Week_1_Arrays_and_Plots.ipynb) - Numpy and Matplotlib
* [Homework Report Template](Report_Template.ipynb) - Use this for all homework
* [LaTeX Crash Course](intro/LaTeX_Crash_Course.ipynb) - How to make nice equations
* [How Numbers are Stored](intro/Week_2_How_Numbers_are_Stored.ipynb) - Unavoidable errors in computing, and the central conflict for the semester

## Systems of Linear Equations
* [Linear Algebra Review](linear/Week_2_Linear_Systems.ipynb) - Linear Algebra for solving systems of linear equations

## Root Finding
* [Root Finding Class](roots/Week_4_Root_Finding.ipynb) - Root finding methods (bisection, Newton, Secant) and root_scalar
* [In-class Problem](roots/Week_4_Root_Finding_Problem.ipynb) | [Solution](roots/Week_4_Root_Finding_Solutions.ipynb)
* [Multi-Dimensional Roots](roots/Week_5_Multi_Roots.ipynb) - Using *root* to solve non-linear systems

## Fitting and Interpolation
* [Fitting Polynomials](fits/Week_5_Fitting_Polynomials.ipynb) - examples of *polyfit* and *polyval*
* [Linear Algebra Fits](fits/Week_6_Linear_Algebra_Fits.ipynb) - how *polyfit* works and a methods comparison
* [Interpolation](fits/Week_6_Interpolation.ipynb) - using *interp1d*

## Derivatives
* [First Derivative Intro](calc/Week_7_Derivative_Intro.ipynb) - example of forwards, backwards, and centered differences
* [Derivative Examples](calc/Week_7_Derivatives.ipynb) - using *gradient*, *derivative*, and splines for data points and functions

## Integrals

## Differential Equations
* [Euler's Method](ode/Week_9_Euler.ipynb) - simple method for IVP
* [Solve IVP](ode/Week_10_solveivp.ipynb) - examples using *scipy.integrate.solve_ivp* including t_eval, events, and stiff problems
* [IVP Fits](ode/Week_10_IVP_Fits.ipynb) - using data points to fit parameters in *solve_ivp*
* [BVP Shooting Methods](ode/Week_11_BVP.ipynb) - using the shooting method to solve BVP with trial-and-error
* [Solve BVP](ode/Week_11_solvebvp_demo.ipynb) - showing how to use *scipy.integrate.solve_bvp*
