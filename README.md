# Recommendation_Systems_study
Comparison of performance evaluation of the baseline and hybrid recommendation systems using various metrics, to prove that hybrid systems perform better.
We used movielens 100k dataset from movielens website.


README file
------------

Requirements:
Python 3.7
Numpy 1.14.6
pandas 1.0.1
matplotlib
surprise 1.1
sklearn 0.22
lightfm 1.15

Installation statements:
pip install numpy
pip install pandas
pip install matplotlib
pip install scikit-surprise
pip install sklearn
pip install lightfm


Dataset:
Movielens and IMDB datasets are present in input folder. Check if the input folder exists. If not present, create a folder 'input' and copy the input files to this location.
Download the dataset from https://grouplens.org/datasets/movielens/latest/, https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset

Four models in four different files:
BaselineKNN.py
BaselineSVD++.py
ProposedHybridSVDContent.py
ProposedLightFM.py

After installing all the required libraries and placing the files in the input folder, run the files using below statements:

python BaselineKNN.py
python BaselineSVD++.py
python ProposedHybridSVDContent.py
python ProposedLightFM.py
