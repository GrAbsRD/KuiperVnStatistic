# KuiperVnStatistic
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
