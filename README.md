# What is this Project?

This is my approach on the "Synthetic Financial Datasets For Fraud Detection" machine learning problem. </br>

The objective here is to try and predict if a certain transaction was legitimate or fraudulent (more on that on the next section). </br>

This project consists in a jupyter notebook with complete EDA and feature engineering explanation.

Kaggle original link: https://www.kaggle.com/datasets/ealaxi/paysim1

These are the contents of this project:

* Exploratory Data Analysis
* Feature Engineering
* Classification Modeling using PyCaret:
    * Model Comparison
    * Model Selection
    * Model Tunning
    * Metrics
    * Prediction


Author: Augusto Gontijo </br>
LinkedIn: https://www.linkedin.com/in/augusto-gontijo/?locale=en_US </br>
GitHub: https://github.com/augusto-gontijo

# Context

There is a lack of public available datasets on financial services and specially in the emerging mobile money transactions domain. Financial datasets are important to many researchers and in particular to us performing research in the domain of fraud detection. Part of the problem is the intrinsically private nature of financial transactions, that leads to no publicly available datasets.

We present a synthetic dataset generated using the simulator called PaySim as an approach to such a problem. PaySim uses aggregated data from the private dataset to generate a synthetic dataset that resembles the normal operation of transactions and injects malicious behaviour to later evaluate the performance of fraud detection methods.

More on: https://www.kaggle.com/datasets/ealaxi/paysim1

# Dependencies

This project was developed using:

* Python Version: 3.8.10
* Numpy version: 1.19.5
* Pandas version: 1.4.1
* SKLearn version: 0.23.2
* pycaret version: 2.3.9
* Seaborn version: 0.11.2
* matplotlib version: 3.5.1

(you might have trouble if trying to use different versions)
