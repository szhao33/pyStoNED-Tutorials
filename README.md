# **pyStoNED** tutorials [![PyPI version](https://img.shields.io/pypi/v/pystoned.svg?maxAge=3600)](https://pypi.org/project/pystoned/) [![Downloads](https://pepy.tech/badge/pystoned/month)](https://pepy.tech/project/pystoned/month) [![Downloads](https://pepy.tech/badge/pystoned)](https://pepy.tech/project/pystoned)

  > **Introduction**

  [`pyStoNED`](https://pypi.org/project/pystoned/) is a Python package that provides functions for estimating Convex Nonparametric Least Square ([`CNLS`](https://pubsonline.informs.org/doi/abs/10.1287/opre.1090.0722)), Stochastic Nonparametric Envelopment of Data ([`StoNED`](https://link.springer.com/article/10.1007/s11123-010-0201-3)), and other various `StoNED`-related variants (e.g., [`CQR`](https://www.sciencedirect.com/science/article/pii/S0140988320300979), [`ICNLS`](https://www.sciencedirect.com/science/article/abs/pii/S0377221713004748)). It allows the user to estimate the StoNED-related models in an open-access environment rather than in commercial software (e.g., `GAMS` and `MATLAB`).

  > **Data description**

  + [Finnish electricity distribution firms](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Data/Finnish%20firms.ipynb)
  + [OECD countries](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Data/OECD%20countries.ipynb)

  > **StoNED-related models estimation**

  + Convex Nonparametric Least Square (`CNLS`)
    + [Production function](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/CNLS/CNLS_prod.ipynb)
    + [Cost function](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/CNLS/CNLS_cost.ipynb)

  + Stochastic Nonparametric Envelopment of Data (`StoNED`)
    + [Log-transformed cost function estimation and residual decomposition by MoM](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/StoNED/StoNED.ipynb)
    + Estimating unconditional expected inefficiency (`mu`) by KDE

  + Corrected Convex Nonparametric Least Squares (C<sup>2</sup>NLS)

  + Convex quantile approaches (`CQR` and `CER`)
    + [Convex Quantile Regression](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/CQR/CQR.ipynb)
    + [Convex Expectile Regression](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/CQR/CER.ipynb)
 
  + Monotonic versions
    + Isotonic Convex Nonparametric Least Square (`ICNLS`)
    + Isotonic Convex Quantile Regression (`ICNLS`)
    + Isotonic Convex Expectile Regression (`ICNLS`)
  
  + Multiplicative Composite Error Term

  + Multiple Outputs (DDF Formulation)
    + Undesirable output
    + without undesirable output

  + `Z`-variables
    + [StoNED with Z-variable](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/StoNEZD/StoNEZD.ipynb)

  + Data Envelopment Analysis (`DEA`)
    + [Radial input oriented VRS model](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/DEA/DEA_io_vrs.ipynb)
    + [Radial output oriented VRS model](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/DEA/DEA_oo_vrs.ipynb)
    + [Directional VRS model](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/DEA/DEA_ddf_vrs.ipynb)
    + [Undesirable output (DDF)](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/DEA/DEA_UndesirableOutput.ipynb)
    + [Changing the reference set](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/DEA/DEA_changeReferenceSet.ipynb)   

  > **Comparison with estimates from GAMS**


  > **Appendix**

  + [Function List](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Intro/Function%20List.ipynb) 
  + [List of Acronyms](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Intro/List%20of%20Acronyms.ipynb)
  + [Solver](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Intro/Solver.ipynb)

  > **Extra tutorials**

  + [Rewrite GAMS codes in Python](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Extra/gams2python.ipynb)
  + [A ConcreteModel for CNLS model](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Extra/CNLS_ConcreteModel.ipynb)
  + [A ConcreteModel for DEA model](https://github.com/ds2010/pyStoNED-Tutorials/blob/master/Extra/DEA_ConcreteModel.ipynb)
