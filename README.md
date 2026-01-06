# Red Wine Quality Predictor
We use winequality-red.csv as our dataset to create a machine learning model to predict quality of red wine.

## Goals
The quality of red wine is of great interest to collectors and manufacturers alike since it serves as a good estimator of how much the wine is worth. Our data set includes various attributes that can potentially influence the quality of red wine, such as ... among many others. Applying the right machine learning model, we will be able to accurately predict what the quality of the red wine will be, allowing collectors, manufacturers (and even you!) to make relevant changes to increase quality of the product.


## Dataset
* __Filename:__ [winequality-red.csv](winequality-red.csv)
* __Source:__ [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)


## How to use this project
1. __Clone the repo:__ `git clone https://github.com/tristan0huang/WineData`
2. __Install libraries:__ `pip install pandas tensorflow matplotlib seaborn scikit-learn (on Terminal)`
3. __Install libraries:__ `!pip install pandas tensorflow matplotlib seaborn scikit-learn (on colab)`
4. __Run model:__ `python ML_model.ipynb`

   You might encounter "ImportError : No Moduled Name "tensorflow" when running "import tensorflow as tf". 

   To solve this, you can uninstall tensorflow and then reinstall it by pip uninstall tensorflow + pip install tensorflow in terminal.

   If you encounter "ERROR: Could not install packages due to an OSError: [Errno 2] No such file or directory" 

   and "HINT: This error might have occurred since this system does not have Windows Long Path support enabled"

   the most easy way to solve this is going into the registry editor with this directory "Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem", 

   and thening edit "LongPathsEnabled" to a value of 1. Then it should be done.


## Link to Jupyter Notebook
[Jupyter Notebook](ML_model.ipynb)
