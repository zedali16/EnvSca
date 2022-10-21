Summary:

    - R code for “Interpretable Classification of Categorical Time Series Using the SpectralEnvelope and Optimal Scalings” by Li, Bruce, and Cai (2022)

Description:

    - functions.r: contains all necessary functions to run simulations.

    - demo_case1.r: demonstrates the proposed method for Case 1 in the simulation studies.

    - demo_case2.r: demonstrates the proposed method for Case 1 in the simulation studies.

    - demo_case3.r: demonstrates the proposed method for Case 1 in the simulation studies.

    - seql executables (folder): contains necessary C++ implementation of the sequence learner  (Ifrim and Wiuf, 2011).

Dependencies:
Code was developed using R version 4.0.2 ("Taking Off Again"), so code may not function properly on older versions of R. The packages listed in the demo file must also be installed prior to use: astsa, abind.

Code has been tested and developed for data of the following dimensions: <= 500 time points (T), <= 20 training time series, <= 100 testing time series. Larger datasets may require more RAM for processing.
