# Randomized Optimization
## Overview
This repository runs 4 randomized optimization algorithms: Randomized Hill Climbing, Simulated Annealing, Genetic Algorithm and MIMIC. First, we analyze these algorithms’ performance in determining weights in Artificial Neural Networks. Next, we look at the performance of these algorithms on 3 optimization problems: Travelling Salesman, Continuous Peaks and Flip Flop.

Datasets used was Adult data set from UCI machine learning repository.
## Steps to Run
1. Requires Python 3.6
2. Install following requirements:
* numpy == 1.15.1
* scipy == 1.1.0
* scikit-learn == 0.20.0
* pandas == 0.23.4
* xlrd == 0.9.0
* matplotlib == 2.2.3
* seaborn == 0.9.0
* scikit-optimize == 0.5.2
* kneed == 0.1.0
2. Run following files with jython to create the data files
* NN-Backprop.py
* NN-GA.py
* NN-RHC.py
* NN-SA.py
* continuoutpeaks.py
* flipflop.py
* tsp.py
4. Run plotting.py with python3 to generate charts
## Results Obtained
Refer Analysis.pdf for more information on the results obtained.
![Picture1](/results/Picture1.png)
![Picture2](/results/Picture2.png)
![Picture3](/results/Picture3.png)
![Picture4](/results/Picture4.png)
![Picture5](/results/Picture5.png)
![Picture6](/results/Picture6.png)
