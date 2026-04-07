# Taming Probabilistic, High-dimensional Data

Tutorial materials for the DANGER Workshop -- Banff, Apr 8 2026 -- by Jessica N. Howard (<jnhoward@ucsb.edu>).


This tutorial contains notebooks and data which are a part of the hands-on component of the third tutorial session: "Techniques Session 3: Tips and tricks for analyzing and presenting results" (1h30 total).

There are two notebooks which are part of this session:

- `buildYourOwnROCcurve.ipynb`: To build intuition for the underlying statistical meaning, this notebook walks through how one would construct a Receiver Operating Characteristic (ROC) curve. ROC curves are used to assess binary classification performance. 

- `estimateUncertainty.ipynb`: This notebook looks at several methods for estimating the uncertainty on a metric from a set of data samples and compares them on a set of mystery data whose true parameter value is known.

As well as the supplementary files:

- `mysteryData.npy`: File containing the data accompanying `estimateUncertainty.ipynb`.

- `requirements.txt`: File containing the library requirements for this tutorial.