# Homework 2 - eCommerce analytics

This repository contains the files for the HW2. The `MAIN_COMPLETO.ipynb` file contains the answers organized in sections.
## Before we start
In order to excecute the code on all the months we did all the computation on a *AWS-EC2* instance. We did some useful and computationally expensive operations on the dataset and we saved the results with the `pickle` format provided by Python. This allowed us to load faster the objects, not overcharge the RAM memory and avoid kernel shutdown. Some of the operation that we performed outside the notebook are:
- dividing the `category_code`, from the format `category_level_0.category_level_1.category_level_3` (like `furniture.living_room.sofa`) to the first level category and subcategory in two other columns `Category` and `Subcategory`;
- dateparsing (`pickle` maintains the `datetime` objects);
- some groupby operations (like in RQ1).

All the loaded preprocessed dataframes are explained in detail when loaded in the `main.ipynb`. In the `images` folder there are two screenshots of the s3 bucket with all the preprocessed files. Below there is the link for *nbviewer*

> https://nbviewer.jupyter.org/github/domenicocinque/ADM-HW2/blob/main/MAIN_COMPLETO.ipynb
