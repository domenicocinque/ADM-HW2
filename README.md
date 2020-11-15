# Homework 2 - eCommerce analytics

This repository contains the files for the HW2. The `main.ipynb` file contains the answers organized in sections.

## Before we start
In order to excecute the code on all the months we did all the computation on a *AWS-EC2* instance. Since the instance RAM was not sufficient, in addition we did some preprocessing of the data as:
- saving the files using the `pickle` module provided by Python. This permitted us to load faster the objects and save dataframes with already perfomed operations, like the `datetime` conversion;
- performing some subsetting and heavy operations outside the notebook (e.g. groupby).


