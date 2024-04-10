# KuiperVnStatistic
BibTeX Item for Citation with LaTeX:
@article{ZHANG2024e28274,
title = {Fixed-point algorithms for solving the critical value and upper tail quantile of Kuiper's statistics},
journal = {Heliyon},
volume = {10},
number = {7},
pages = {e28274},
year = {2024},
issn = {2405-8440},
doi = {https://doi.org/10.1016/j.heliyon.2024.e28274},
url = {https://www.sciencedirect.com/science/article/pii/S2405844024043056},
author = {Hong-Yan Zhang and Wei Sun and Xiao Chen and Rui-Jia Lin and Yu Zhou},
keywords = {Kuiper's statistic, Upper tail quantile, Fixed-point algorithm, Numerical approximation, Algorithm design, STEM education},
}


Code for Kuiper's Vn statistic in the Goodness-of-fit Test in Mathematical Statistics 

/*********** Compile+Link+Run at Unix/Linux terminal *****************
 * Compile+Link:   $ gcc KuiperPairSolver.c main.c -o Kuiper -lm
 *           or    $ g++ KuiperPairSolver.c main.c -o Kuiper
 * Run:            $ ./Kuiper 0.05 100  1  1  2.45
 *                 $ ./Kuiper 0.05 100  1  2  2.45 
 *                 $ ./Kuiper 0.05 100  2  1  2.45 >> test.txt
 *                 $ ./Kuiper 0.05 100  2  2  2.45 >> test.txt
 * 
 * Note that the initial value is important for the iteration and our
 * suggestions are as follows:
 *    V_n test, direct iterative method, guess in (0.5, 2.5)
 *    V_n test, Newton iterative method, guess in (1.1, 2.5)
 *    V_{n,n} test, direct iterative method, guess in (2.4, 2.6)
 *    V_{n,n} test, direct iterative method, guess in (2.2, 2.6)
 *  optional guess for all of most applications, guess = 2.45
 *  Newton iterative method works well for both V_n and V_{n,n} test  
 * *******************************************************************/


