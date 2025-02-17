# Life-Expectancy-Model
Predicting age at death, of given individual, given the following data:
- **Country**
- **Year**
- **Status**
- **Life expectancy**
- **Adult Mortality**
- **Infant deaths**
- **Alcohol**
- **Percentage expenditure**
- **Hepatitis B**
- **Measles**
- **BMI**
- **Under-five deaths**
- **Polio**
- **Total expenditure**
- **Diphtheria**
- **HIV/AIDS**
- **GDP**
- **Population**
- **Thinness 1-19 years**
- **Thinness 5-9 years**
- **Income composition of resources**
- **Schooling**

Data was properly selected first, then split into
the train, validation and test sets, was cleansed,
properly imputed, without any data leakages,
preprocessed, and correctly reasoned, then converted into
numbers, just after One Hot Encoding and MinMax normalization,
the models were created with diligence to their architectures,
and the resulting regression model, has achieved a very good result
being +-1.2 year wrong on average for the individuals, with
a very good confidence intervals, thus the problem was solved,
in future I may fine tune it even further this time using a proper tool for this, in my case: Optuna.


## How to run the code
### Option 1:
Via google collab, everythin is set, to work there,
and thus you just need a google account, log in to google collab,
and then upload a LifeExpectancyModel.ipynb file,
and simply run it, and everything will work fine.
### Option 2:
You can run it on the environment with python and
required frameworks/libraries (provided below), most
preferably, you should use Conda, and Jupyter Notebook,
with all of the libraries and framewroks installed,
you should upload a LifeExpectancyModel.ipynb file,
to Jupyter Notebook, and within the same directtory,
you must upload, a data.csv file, from my github repo,
were you to put it elsewhere, you shall change the path,
in the proper cell, at the end after you'd do everythin needed,
you shall comment, checked lines within the jupyter notebook
code, I pinned them with the comment to their right.
After all of this code will work properly.

## The provided code works with the following libraries (wasn't tested on the other ones):
TensorFlow version: 2.18.0  
NumPy version: 1.26.4  
Matplotlib version: 3.10.0  
Pandas version: 2.2.2  
Scikit-learn version: 1.6.1  
Python version: 3.11.11 (main, Dec  4 2024, 08:55:07) [GCC 11.4.0]

"And these are the only libraries, and frameworks you need."