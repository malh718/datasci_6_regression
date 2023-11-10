# datasci_6_regression
Part 1


## 1. Simple Linear Regression
In this dataset we are looking at dataset titled Heart failure clinical record  by UC Irvine. The variable names are age, anemia, CPK, diabetes, ejection_fraction, BP, platelets, serum_creatinine, serum_sodium, sex, smoking, time and death event.


Our first steps include importing over all the packages you need. 
Which are: 
import pandas as pd
import pandas as pd
import statsmodels.api as sm
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats

from statsmodels.stats.diagnostic import linear_rainbow
from scipy.stats import shapiro
from statsmodels.stats.diagnostic import het_goldfeldquandt

And then the dataset had an option that let us import in python following the instructions they had, I was able to import. And I did df to see I had 299 row and 12 columns. 

<img width="506" alt="Screen Shot 2023-11-10 at 3 44 02 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/c3a6feaf-5bcb-4ddb-9cb4-1dfc6555264a">

Diabetes and Platelets 
In this dataset diabetes represents whether a person has diabetes or not. This is the independent variable.
The platelets are the platelets in  the blood in kiloplatelets/mL. This represents the dependent variable.
I will be looking at the relationship between the two and how whether having diabetes may affect your platelet count. 
