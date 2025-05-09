# GaussianHCRB-SDP

The notebook `GaussianHCRB-Applications.ipynb` contains the SDP to compute the Holevo Cramér-Rao bound for Gaussian quantum states, as explained in [arXiv:2504.17873](https://arxiv.org/abs/2504.17873) by S. Chang, M. G. Genoni and F. Albarelli.
The code is applied to the two applications discussed in the paper and reproduces the two figures in the manuscript.

> [!IMPORTANT]  
> This code relies on `cvxpy`, `numpy` and `matplotlib` for plotting, the `mosek` package is also used as a solver, but it's optional.
