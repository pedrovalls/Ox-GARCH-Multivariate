# Ox-GARCH-Multivariate

This repository has programmes to estime VAR models and alsno MGARCH models

The VAR(0)_DLPETR4_DLIBOV.fl is a batch programme in Ox to estimate a VAR(0)
for DLPETR4_Per and DLIBOV_Per.

The EWMA-Multivariado.fl is a batch programme in Ox to estimate an Multivariate EWMA 
for the vector $y_{t}=(DLIBOV_{t} : DLPETR4_{t})$, using the same $\lambda = 0.94$.

The Ox-GARCH-BEKK-Scalar-Diagional is a batch programme in Ox to estimate an Multivariate
BEKK scalar or diagonal using:

$\bf{H}_{t}$
=$\bf{C}^{\prime }\bf{C}$+$\sum\limits_{i=1}^{p}\bf{A}_{i}^{\prime }(\bf{\epsilon }_{t-i}\bf{\epsilon }_{t-i}^{\prime})\hbf{A}_{i}$+$\sum\limits_{j=1}^{q}\mathbf{B}_{j}^{\prime}\mathbf{H}_{t-j}\mathbf{B}_{j}$

onde\ $\mathbf{C}$ \'{e} uma matriz triangular superior$,$ $\mathbf{A}_{i}$
(para $i=1,...,p$) e $\mathbf{B}_{j}$ (para $j=1,...,q$) s\~{a}o matrizes
quadradas. A especifica\c{c}\~{a}o no Ox permite que estas matrizes sejam
diagonais ou escalares.
