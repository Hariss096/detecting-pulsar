**Detecting Pulsar**

Introduction to Data Science - Udacity Project

Dataset information and files can be downloaded from:
https://archive.ics.uci.edu/ml/datasets/HTRU2

Medium blog post explaining the steps:
https://medium.com/@hariss096/detecting-pulsar-26374beda790

**Libraries used:**
- pandas
- sci-kit learn
- scipy
- numpy
- matplotlib

**Motivation**
As a machine learning student who watches documentaries related to cosmology and astrophysics in his spare time, this dataset is perfect for me to learn and have fun along the way.

**Files inside the repository**
- pulsar_stars.csv (Downloaded from UCI Machine learning repository, linked provided above).
- code.ipynb (A jupyter notebook file that follows a CRISP-DM approach for analyzing the dataset).
- .gitignore (To exclude ipynb checkpoints folder from being pushed into remote).

**Insights**
The modelling helps in identifying if the detected object is a pulsar or not (with 95% precision) when following 8 values of the object are provided:
- Mean of integrated profile
- Standard deviation of integrated profile
- Excess kurtosis of integrated profile
- Skewness of integrated profile
- Mean of DM-SNR curve
- Standard deviation of DM-SNR curve
- Excess kurtosis of DM-SNR curve
- Skewness of DM-SNR curve

Details about each of these features can be found in this book:
http://www.scienceguyrob.com/wp-content/uploads/2016/12/WhyArePulsarsHardToFind_Lyon_2016.pdf
The formulas for each of the features are listed in page number 222 of this book.
