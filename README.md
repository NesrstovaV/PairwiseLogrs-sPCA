# Identifying important pairwise logratios (PLRs) using sparse PCA (sPCA)

The proposed method to identify important pairwise logratios (and parts) using sparse PCA (introduced in "Erichson, N. B., Zheng, P., Manohar, K., Brunton, S. L., Kutz, J. N., Aravkin, A. Y. (2020). Sparse principal component analysis via variable projection. SIAM Journal on Applied Mathematics 80(2):977–1002") is introduced in "Nesrstová, V., Wilms, I., Hron, K., Filzmoser, P. Identifying Important Pairwise Logratios in Compositional Data with Sparse Principal Component Analysis" (currently under revision; November 2023).

## Requirements
Calculations were performed in following software, using the listed libraries:
- R version: 4.1.3 (2022-03-10) -- "One Push-Up"
- Essential libraries:
    - sparsepca: for sparse PCA; version 0.1.2
    - easyCODA: for STEP; version 0.34.3
    - compositions: to handle compositional data; version 2.0-4

## Available scripts
1. Auxiliary functions
   Set of functions to create sPCA models, simulations and visualisation.
2. Simulations (for both D = 10 and D = 20); D = number of compositional parts

   a) Scenario A: balanced amount of relevant and noise balances to generate data

   b) Scenario B: more relevant balances 

   c) Scenario C: more noise balance
3. Real data applications
Empirical data sets Aar and archaeometric data set (cups).

   a) Aar massif data set

   b) Archaeometric data set
6. Toy example

An easy-to-use example of how to perform the calculations and obtain the matrix of sparse loadings.
