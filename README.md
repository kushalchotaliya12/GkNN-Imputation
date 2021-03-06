# GkNN-Imputation
Missing Data Imputation using Gray kNN Algorithm

## About GkNN

Existing kNN method is used to find missing data and it follows Minkowski distance rule. This algorithm is more productive towards numerical dataset like features or attributes but not for mixed type dataset. To make kNN method more efficient for heterogeneous data, we propose GkNN (Gray k – Nearest Neighbor) imputation method to iteratively imputing missing data. It is designed according to gray distance, in which it selects k nearest neighbors for each missing data and calculates distance between missing and training data. This gray distance metric can deal with both numerical and categorical dataset.

## Algorithm

The algorithm and logic behind Gray kNN can be found in the research paper by <b>Shichao Zhang</b> linked below: <br/>
[https://www.sciencedirect.com/science/article/abs/pii/S0164121212001586]

## Implementation 

Above iPython Notebooks consist the practical execution of Gray kNN Imputation using Python 3.8
