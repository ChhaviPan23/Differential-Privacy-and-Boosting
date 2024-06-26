# Boosting and Differential Privacy

Mehta Family School of Data Science and AI\
Chhavi

#### DA-204 (AI) Course Project
https://privacytools.seas.harvard.edu/files/privacytools/files/05670947.pdf


## Environment

Evaluation environment: Python 3.10.12, NumPy 1.25.2, SciPy 1.11.4, scikit-learn 1.2.2, collection 0.1.6

## Results

The following image shows the result of the randomly selected query by running the boosting algorithm for 20 times. The dots represent the result of query we got for running the algorithm 20 times and the  horizontal line is the true answer to the query.

![image](https://github.com/ChhaviPan23/Differential-Privacy-and-Boosting/assets/138955514/54600e2a-5a2f-4673-8fed-9633affd093b)


## Training and evaluation 

Use the following code to evaluate the boosting algorithm and get results for different random queries.

> python 22125011_Chhavi.py

## Dataset
We have used the california housing dataset but since there are limitations on data size and queries as defined in paper, we are choosing only first 2000 enteries of the dataset.
Although we have loaded the dataset from the scikit learn library but the link of the data is provided below
https://www.kaggle.com/datasets/camnugent/california-housing-prices


## Platform to run 
The code can simply be run on pc or google colab.
