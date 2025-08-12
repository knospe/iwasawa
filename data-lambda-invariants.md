# Numerical data for the paper *[Special values of p-adic L-functions and Iwasawa λ-invariants of Dirichlet characters](https://arxiv.org/abs/2401.06100)* 


For most computations, we use the special values of the first set of
parameters (see Section 2 of the paper). We assume
that $`\chi = \theta \omega^i`$ where $`p`$ does not divide the conductor of
$`\theta`$. In the rank one case, the $`p`$-th generalized Bernoulli
number of $`\theta = \chi \omega^{-1}`$ and the derivative
$`L'_p(0,\chi)`$ (modulo $`p^3`$) are sufficient to distinguish between
the cases $`\lambda=1`$, $`\lambda=2`$ and $`\lambda >2`$. In the rank
zero case, the value $`B_{1,\theta}`$ is also needed. Furthermore, in
order to compute $`\lambda`$-invariants $`\geqslant 3`$, we use the
$`k`$-th generalized Bernoulli numbers (where $`k=1,\dots,p-1`$) of
$`\theta`$ and $`\theta \psi`$ (where $`\psi`$ has order $`p^n`$), as
described in part (2) of Theorem 5.2 of the paper, 
starting with $`n=1`$ and
increasing $`n`$ if necessary.



## Distribution of $`\lambda`$-invariants in the rank one case

First, we provide numerical data for the rank one case and fixed primes
$`p`$. In this situation, the predicted distribution of
$`\lambda`$-values should be shifted by $`1`$.

Using the above formulas, we computed the $`\lambda`$-invariants of
$`\chi = \theta \omega`$, where $`\theta`$ is odd of conductor
$`<100,000`$ and $`\theta(p)=1`$. The first row gives the predicted
distribution and the second row contains the number $`N`$ of tested
characters as well as the computed proportions. For $`p=3`$ and
$`\text{\rm ord}(\theta)=2`$ we still see a larger deviation from the
prediction (compare ), but the difference becomes smaller as we compute
$`\lambda`$-invariants of characters with larger conductor.

$`p=3`$, $`ord(\theta)=2`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.5601`$ | $`0.2801`$ | $`0.1050`$ | $`0.0364`$ | $`0.0123`$ | $`0.0041`$ | $`0.0020`$ |
| $`N=11404`$ | $`0.6121`$ | $`0.2604`$ | $`0.0835`$ | $`0.0296`$ | $`0.0092`$ | $`0.0035`$ | $`0.0017`$ |

  
$`p=3`$, $`ord(\theta)=4`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8766`$ | $`0.1096`$ | $`0.0123`$ | $`0.0014`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ |
| $`N=17732`$ | $`0.8901`$ | $`0.0976`$ | $`0.0108`$ | $`0.0014`$ | $`0.0001`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=5`$, $`ord(\theta)=2`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.7603`$ | $`0.1901`$ | $`0.0396`$ | $`0.0080`$ | $`0.0016`$ | $`0.0003`$ | $`0.0001`$ |
| $`N=12667`$ | $`0.7782`$ | $`0.1768`$ | $`0.0367`$ | $`0.0072`$ | $`0.0007`$ | $`0.0003`$ | $`0.0001`$ |

  
$`p=5`$, $`ord(\theta)=4`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.7603`$ | $`0.1901`$ | $`0.0396`$ | $`0.0080`$ | $`0.0016`$ | $`0.0003`$ | $`0.0001`$ |
| $`N=12679`$ | $`0.7662`$ | $`0.1834`$ | $`0.0414`$ | $`0.0072`$ | $`0.0013`$ | $`0.0001`$ | $`0.0003`$ |

  
$`p=5`$, $`ord(\theta)=6`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.9584`$ | $`0.0399`$ | $`0.0016`$ | $`0.0001`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |
| $`N=37291`$ | $`0.9578`$ | $`0.0407`$ | $`0.0015`$ | $`0.0001`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=7`$, $`ord(\theta)=2`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8368`$ | $`0.1395`$ | $`0.0203`$ | $`0.0029`$ | $`0.0004`$ | $`0.0001`$ | $`0.0000`$ |
| $`N=13299`$ | $`0.8419`$ | $`0.1341`$ | $`0.0207`$ | $`0.0030`$ | $`0.0002`$ | $`0.0000`$ | $`0.0001`$ |

  
$`p=7`$, $`ord(\theta)=4`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9792`$    | $`0.0204`$    | $`0.0004`$              |
| $`N=21244`$ | $`0.9797`$    | $`0.0197`$    | $`0.0007`$              |

  
$`p=7`$, $`ord(\theta)=6`$  

|  | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8368`$ | $`0.1395`$ | $`0.0203`$ | $`0.0029`$ | $`0.0004`$ | $`0.0001`$ | $`0.0000`$ |
| $`N=27049`$ | $`0.8360`$ | $`0.1419`$ | $`0.0187`$ | $`0.0029`$ | $`0.0003`$ | $`0.00004`$ | $`0.00004`$ |

  
$`p=11`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9008`$    | $`0.0901`$    | $`0.0091`$              |
| $`N=13931`$ | $`0.9058`$    | $`0.0847`$    | $`0.0095`$              |

  
$`p=11`$, $`ord(\theta)=4`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9917`$    | $`0.0083`$    | $`0.0001`$              |
| $`N=23252`$ | $`0.9895`$    | $`0.0104`$    | $`0.0001`$              |

  
$`p=11`$, $`ord(\theta)=6`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9917`$    | $`0.0083`$    | $`0.0001`$              |
| $`N=41478`$ | $`0.9920`$    | $`0.0079`$    | $`0.0002`$              |

  
$`p=13`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9172`$    | $`0.0764`$    | $`0.0064`$              |
| $`N=14110`$ | $`0.9199`$    | $`0.0728`$    | $`0.0073`$              |

  
$`p=13`$, $`ord(\theta)=4`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9172`$    | $`0.0764`$    | $`0.0064`$              |
| $`N=18806`$ | $`0.9210`$    | $`0.0726`$    | $`0.0064`$              |

  
$`p=13`$, $`ord(\theta)=6`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9172`$    | $`0.0764`$    | $`0.0064`$              |
| $`N=36440`$ | $`0.9189`$    | $`0.0743`$    | $`0.0068`$              |

  
$`p=17`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9377`$    | $`0.0586`$    | $`0.0037`$              |
| $`N=14352`$ | $`0.9392`$    | $`0.0575`$    | $`0.0033`$              |

  
$`p=19`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9446`$    | $`0.0525`$    | $`0.0029`$              |
| $`N=14441`$ | $`0.9463`$    | $`0.0504`$    | $`0.0033`$              |

  
$`p=23`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9546`$    | $`0.0434`$    | $`0.0020`$              |
| $`N=14569`$ | $`0.9552`$    | $`0.0428`$    | $`0.0020`$              |

  
$`p=29`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9643`$    | $`0.0344`$    | $`0.0012`$              |
| $`N=14695`$ | $`0.9666`$    | $`0.0324`$    | $`0.0010`$              |

  
$`p=31`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9667`$    | $`0.0322`$    | $`0.0011`$              |
| $`N=14728`$ | $`0.9659`$    | $`0.0328`$    | $`0.0013`$              |

  
$`p=31`$, $`ord(\theta)=6`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9667`$    | $`0.0322`$    | $`0.0011`$              |
| $`N=41770`$ | $`0.9672`$    | $`0.0318`$    | $`0.0011`$              |

  
$`p=37`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9722`$    | $`0.0270`$    | $`0.0008`$              |
| $`N=14789`$ | $`0.9734`$    | $`0.0260`$    | $`0.0007`$              |

  
$`p=41`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9750`$    | $`0.0244`$    | $`0.0006`$              |
| $`N=14841`$ | $`0.9749`$    | $`0.0245`$    | $`0.0007`$              |

  
$`p=43`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9762`$    | $`0.0232`$    | $`0.0006`$              |
| $`N=14856`$ | $`0.9768`$    | $`0.0228`$    | $`0.0004`$              |

  
$`p=43`$, $`ord(\theta)=6`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9762`$    | $`0.0232`$    | $`0.0006`$              |
| $`N=46382`$ | $`0.9777`$    | $`0.0218`$    | $`0.0005`$              |

  
$`p=47`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9783`$    | $`0.0213`$    | $`0.0005`$              |
| $`N=14884`$ | $`0.9789`$    | $`0.0204`$    | $`0.0007`$              |

  
$`p=97`$, $`ord(\theta)=2`$  

|             | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda \geqslant 3`$ |
|:------------|:--------------|:--------------|:------------------------|
| predicted   | $`0.9896`$    | $`0.0103`$    | $`0.0001`$              |
| $`N=15040`$ | $`0.9897`$    | $`0.0102`$    | $`0.0001`$              |

## Primes with $`\lambda>1`$ in the rank one case

We identify small primes and fields of small degree
for which the $`\lambda`$-invariant exceeds $`1`$ in the rank one case.
We fixed an odd character $`\theta`$ and utilized Theorem
3.2 (i) to compute
all small primes $`p`$ such that $`L_p(s,\theta \omega)`$ has a trivial
zero and $`\lambda_p(\theta \omega)>1`$. This was also done by Dummit et
al. for imaginary quadratic characters. Below, we list the
combinations of characters $`\chi = \theta \omega`$ of order $`<10`$,
conductor $`<100`$ and primes $`p<500`$ having a trivial zero and
satisfying $`\lambda_p(\chi)>1`$. For a fixed character, we expect that the number of such primes $`p`$ with $`p \leqslant X`$ is
$`O(\log(\log(X))`$. Furthermore, almost all of these primes should have
residue class degree $`f=1`$, i.e., only a finite number is expected to
have degree $`f \geqslant 2`$.  

| order | conductor | field                      | primes                 |
|:------|:----------|:---------------------------|:-----------------------|
| $`2`$ | $`3`$     | $`\mathbb{Q}(\sqrt{-3})`$  | $`13`$, $`181`$        |
| $`2`$ | $`11`$    | $`\mathbb{Q}(\sqrt{-11})`$ | $`5`$                  |
| $`2`$ | $`19`$    | $`\mathbb{Q}(\sqrt{-19})`$ | $`11`$                 |
| $`2`$ | $`24`$    | $`\mathbb{Q}(\sqrt{-6})`$  | $`131`$                |
| $`2`$ | $`31`$    | $`\mathbb{Q}(\sqrt{-31})`$ | $`227`$                |
| $`2`$ | $`35`$    | $`\mathbb{Q}(\sqrt{-35})`$ | $`3`$, $`13`$          |
| $`2`$ | $`47`$    | $`\mathbb{Q}(\sqrt{-47})`$ | $`3`$, $`17`$, $`157`$ |
| $`2`$ | $`51`$    | $`\mathbb{Q}(\sqrt{-51})`$ | $`5`$                  |
| $`2`$ | $`52`$    | $`\mathbb{Q}(\sqrt{-13})`$ | $`113`$                |
| $`2`$ | $`56`$    | $`\mathbb{Q}(\sqrt{-14})`$ | $`3`$                  |
| $`2`$ | $`71`$    | $`\mathbb{Q}(\sqrt{-71})`$ | $`29`$                 |
| $`2`$ | $`83`$    | $`\mathbb{Q}(\sqrt{-83})`$ | $`17`$, $`41`$         |
| $`2`$ | $`84`$    | $`\mathbb{Q}(\sqrt{-21})`$ | $`107`$, $`173`$       |
| $`2`$ | $`88`$    | $`\mathbb{Q}(\sqrt{-22})`$ | $`23`$, $`29`$         |

| order | conductor | field (polynomial) | prime |
|:---|:---|:---|:---|
| $`4`$ | $`16`$ | $`x^4 + 4 x^2 + 2`$ | $`97`$ |
| $`4`$ | $`29`$ | $`x^4 + x^3 + 4 x^2 + 20 x + 23`$ | $`181`$ |
| $`6`$ | $`9`$ | $`x^6 + x^3 + 1`$ | $`19`$ |
| $`6`$ | $`19`$ | $`x^6 + x^5 + 2 x^4 - 8 x^3 - x^2 + 5 x + 7`$ | $`7`$ |
| $`6`$ | $`28`$ | $`x^6 + 5 x^4 + 6 x^2 + 1`$ | $`337`$ |
| $`6`$ | $`39`$ | $`x^6 - x^5 + 5 x^4 + 6 x^3 + 15 x^2 + 4 x + 1`$ | $`31`$ |
| $`6`$ | $`52`$ | $`x^6 + 13 x^4 + 26 x^2 + 13`$ | $`31`$ |
| $`6`$ | $`63`$ | $`x^6 - 28 x^3 + 343`$ | $`193`$ |
| $`6`$ | $`63`$ | $`x^6 + 35 x^3 + 343`$ | $`241`$ |
| $`6`$ | $`91`$ | $`x^6 - x^5 + 21 x^4 - 22 x^3 + 58 x^2 + 23 x + 155`$ | $`31`$ |
| $`8`$ | $`85`$ | $`x^8 - x^7 + 10 x^6 + 6 x^5 + 49 x^4 - 129 x^3 + 500 x^2 + 2044 x + 1616`$ | $`433`$ |
| $`8`$ | $`96`$ | $`x^8 + 24 x^6 + 180 x^4 + 432 x^2 + 162`$ | $`17`$ |

  

All primes listed above have residue class degree $`f=1`$, but we have
also found some examples of primes (for characters of conductor
$`>100`$) with $`f=2`$ (see below). Looking at the estimated probability, it is not surprising that
these primes are small.  

| order | conductor | field (polynomial) | prime |
|:---|:---|:---|:---|
| $`4`$ | $`187`$ | $`x^4 - x^3 + 45 x^2 + x + 562`$ | $`19`$ |
| $`6`$ | $`259`$ | $`x^6 - x^5 + 22 x^4 + 398 x^3 + 1051 x^2 - x + 23605`$ | $`5`$ |
| $`8`$ | $`187`$ | $`x^8 - x^7 + 44 x^6 - 45 x^5 + 423 x^4 - 877 x^3 + 1826 x^2 - 3515 x + 4591`$ | $`13`$ |

  

## Distribution of $`\lambda`$-invariants in the rank zero case

We provide data for the rank zero case and supplement the numerical data
given in a paper by Delbourgo and Knospe (2022). With the new formulas of this article, we computed the
$`\lambda`$-invariants of $`\chi = \theta \omega^ i`$, where $`\theta`$
is odd of conductor $`<100,000`$ and $`\theta(p) \neq 1`$ if $`i=1`$.  The first row gives the predicted
distribution and the second row contains the number $`N`$ of tested
characters as well as the computed proportions.  

$`p=3`$, $`ord(\theta)=2`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.5601`$ | $`0.2801`$ | $`0.1050`$ | $`0.0364`$ | $`0.0123`$ | $`0.0041`$ | $`0.0014`$ | $`0.0007`$ |
| $`N=18988`$ | $`0.6238`$ | $`0.2538`$ | $`0.0820`$ | $`0.0272`$ | $`0.0094`$ | $`0.0025`$ | $`0.0009`$ | $`0.0004`$ |

  
$`p=3`$, $`ord(\theta)=4`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8766`$ | $`0.1096`$ | $`0.0123`$ | $`0.0014`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |
| $`N=89374`$ | $`0.8880`$ | $`0.1004`$ | $`0.0106`$ | $`0.0009`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=3`$, $`ord(\theta)=8`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8766`$ | $`0.1096`$ | $`0.0123`$ | $`0.0014`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |
| $`N=129594`$ | $`0.8819`$ | $`0.1052`$ | $`0.0114`$ | $`0.0013`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=5`$, $`ord(\theta)=2`$, twist $`i=0`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.7603`$ | $`0.1901`$ | $`0.0396`$ | $`0.0080`$ | $`0.0016`$ | $`0.0003`$ | $`0.0001`$ | $`0.0000`$ |
| $`N=25324`$ | $`0.7768`$ | $`0.1752`$ | $`0.0380`$ | $`0.0082`$ | $`0.0014`$ | $`0.0003`$ | $`0.0001`$ | $`0.0000`$ |

  
$`p=5`$, $`ord(\theta)=2`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.7603`$ | $`0.1901`$ | $`0.0396`$ | $`0.0080`$ | $`0.0016`$ | $`0.0003`$ | $`0.0001`$ | $`0.0000`$ |
| $`N=17735`$ | $`0.7827`$ | $`0.1737`$ | $`0.0345`$ | $`0.0074`$ | $`0.0015`$ | $`0.0002`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=5`$, $`ord(\theta)=4`$ , twist $`i=1`$  

| $`N`$       | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda\geqslant 3`$ |
|:------------|:--------------|:--------------|:--------------|:-----------------------|
| predicted   | $`0.7603`$    | $`0.1901`$    | $`0.0396`$    | $`0.0100`$             |
| $`N=93424`$ | $`0.7760`$    | $`0.1790`$    | $`0.0360`$    | $`0.0090`$             |

  
$`p=7`$, $`ord(\theta)=3`$, twist $`i=0`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda=3`$ | $`\lambda=4`$ | $`\lambda=5`$ | $`\lambda=6`$ | $`\lambda\geqslant 7`$ |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| predicted | $`0.8368`$ | $`0.1395`$ | $`0.0203`$ | $`0.0029`$ | $`0.0004`$ | $`0.0001`$ | $`0.0000`$ | $`0.0000`$ |
| $`N=24676`$ | $`0.8407`$ | $`0.1332`$ | $`0.0221`$ | $`0.0035`$ | $`0.0004`$ | $`0.00004`$ | $`0.0000`$ | $`0.0000`$ |

  
$`p=7`$, $`ord(\theta)=4`$, twist $`i=1`$  

|             | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda\geqslant 3`$ |
|:------------|:--------------|:--------------|:--------------|:-----------------------|
| predicted   | $`0.9792`$    | $`0.0204`$    | $`0.0004`$    | $`0.0000`$             |
| $`N=85862`$ | $`0.9805`$    | $`0.0191`$    | $`0.0004`$    | $`0.0000`$             |

  
$`p=7`$, $`ord(\theta)=6`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda\geqslant 3`$ |
|:---|:---|:---|:---|:---|
| predicted | $`0.8368`$ | $`0.1395`$ | $`0.0203`$ | $`0.0034`$ |
| $`N=266777`$ | $`0.8430`$ | $`0.1343`$ | $`0.0197`$ | $`0.0031`$ |

  
$`p=11`$, $`ord(\theta)=6`$, twist $`i=1`$  

|  | $`\lambda=0`$ | $`\lambda=1`$ | $`\lambda=2`$ | $`\lambda\geqslant 3`$ |
|:---|:---|:---|:---|:---|
| predicted | $`0.9917`$ | $`0.0083`$ | $`0.00007`$ | $`0.00000`$ |
| $`N=252356`$ | $`0.9924`$ | $`0.00756`$ | $`0.00004`$ | $`0.00000`$ |

  
