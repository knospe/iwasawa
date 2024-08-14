# Computations in Iwasawa Theory 

This respository contains SageMath code to compute $p$-adic $L$-functions, Iwasawa power series and $\lambda$-invariants of Dirichlet characters $\chi$. The code is based on several papers.

[On Iwasawa lambda-invariants for abelian number fields and random matrix heuristics](https://arxiv.org/abs/2207.06287) is a paper (2023) by Daniel Delbourgo and Heiko Knospe, published in [Math. Comp. 92 (2023), 1817-1836](https://doi.org/10.1090/mcom/3823). 

[Special values of p-adic L-functions and Iwasawa lambda-invariants of Dirichlet characters](https://doi.org/10.48550/arXiv.2401.06100) is a preprint (2024) by Heiko Knospe.

## SageMath Code
[Computation of the values of p-adic L-functions for Dirichlet characters](padic_lfunction_dirichlet.ipynb)   
[Computation of the Iwasawa power series for Dirichlet characters using series expansions](power_series_dirichlet.ipynb)  
[The Iwasawa power series for Dirichlet characters via interpolation of Bernoulli numbers](power_series_interpolation.ipynb)   
[The 𝜆-invariant of the Iwasawa power series for Dirichlet characters via interpolation of Bernoulli numbers](power_series_lambda.ipynb)     
[Proportion of irregular primes for Dirichlet characters of fixed order](irregular.ipynb)

Tables of $\lambda$-invariants for small $\chi$ and $p$ are provided in an [Appendix](https://github.com/knospe/iwasawa/blob/main/Lambda_Invariants_Abelian_Number_Fields_appendix.pdf) to our paper on Iwasawa $\lambda$-invariants for abelian number fields. A text version of the data is available here:    
[Table for p=3](https://github.com/knospe/iwasawa/blob/main/lambda3-1000.txt)   
[Table for p=5](https://github.com/knospe/iwasawa/blob/main/lambda5-1000.txt)   
[Table for p=7](https://github.com/knospe/iwasawa/blob/main/lambda7-1000.txt)   
Note that $\lambda_p(\chi)=0$ if a character is not listed (resp. $\lambda_p(\chi)=1$ in the trivial zero case). The precise conditions are explained in the [Appendix](https://github.com/knospe/iwasawa/blob/main/Lambda_Invariants_Abelian_Number_Fields_appendix.pdf).
The code for the computations of these tables can be found [here](https://github.com/knospe/iwasawa/blob/main/power_series_lambda.ipynb).


## References
Daniel Delbourgo, A Dirichlet series expansion for the $p$-adic zeta-function, Journal of the Australian Math. Society 81 (2006), 215-224.

Daniel Delbourgo, The convergence of Euler products over $p$-adic number fields, Proceedings of the Edinburgh Math. Society 52 (2009), 583-606.

Daniel Delbourgo and Qin Chao, On $\lambda$-invariants attached to cyclic cubic number fields, LMS Journal of Comput. Math. 18 (2015), 684-698.

Daniel Delbourgo and Heiko Knospe, On Iwasawa $\lambda$-invariants for abelian number fields and random matrix heuristics. Math. Comp. 92 (2023), 1817-1836.

Heiko Knospe and Lawrence Washington, Dirichlet series expansions of $p$-adic $L$-functions, Abhandlungen aus dem Mathematischen Seminar der Universität Hamburg 91 (2021), 325-334. Open access at https://link.springer.com/article/10.1007/s12188-021-00244-0.

Heiko Knospe, Special values of $p$-adic L-functions and Iwasawa $\lambda$-invariants of Dirichlet characters. ArXiv e-prints 2401.06100.

Luochen Zhao, Sum expressions for Kubota-Leopoldt $p$-adic $L$-functions, preprint available at https://arxiv.org/abs/2201.08870.
