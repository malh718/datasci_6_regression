# datasci_6_regression
Part 1


In this dataset we are looking at dataset titled Beans by UC Irvine. 

Below I also updated the Wine dataset.

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

And then the dataset had an option that let us import in python following the instructions they had, I was able to import. And I did df to see I had 13611 row and 16 columns. 

<img width="493" alt="Screen Shot 2023-11-10 at 7 03 51 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/68b3c8ad-d41b-4726-8db7-52f93875a3d1">

# BEAN EXAMPLE

Linear Regression

Rainbow Test: stat=2.293642704044083, p-value=3.406720382516076e-250

Shapiro-Wilk Test: W=0.996713399887085, p-value=7.6304208664685e-17

Goldfeld-Quandt Test: F-statistic=0.1806791713822503, p-value=0.9999999999999999

<img width="854" alt="Screen Shot 2023-11-10 at 7 16 19 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/1ba624a8-055a-4699-9819-cba2ed1f30a2">

<img width="859" alt="Screen Shot 2023-11-10 at 7 20 24 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/21b9983c-f559-4d31-ac1d-c2a946c4d952">


<img width="873" alt="Screen Shot 2023-11-10 at 7 16 50 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/99c3656f-312a-4f8f-afaf-957469962c42">

Multiple Linear Regression

Rainbow Test: stat=9.175869531886491, p-value=0.0

Shapiro-Wilk Test: W=0.9338400363922119, p-value=0.0

Goldfeld-Quandt Test: F-statistic=0.18067917138224995, p-value=0.9999999999999999

<img width="850" alt="Screen Shot 2023-11-10 at 7 19 14 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/5cbc3945-c8e1-47c5-921a-89fe7c8073b8">

<img width="903" alt="Screen Shot 2023-11-10 at 7 19 25 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/e24b4419-813e-4b28-8209-35dddc7b603a">

<img width="863" alt="Screen Shot 2023-11-10 at 7 19 40 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/3f05d95f-08d3-4d17-8f6e-146a727aff0c">


# WINE EXAMPLE 
I also added my Wine example, as I cleaned it up and explained the information. 

Linear Regression
Rainbow Test: stat=2.3899371469856194, p-value=3.0882100589536056e-05

Shapiro-Wilk Test: W=0.9456958174705505, p-value=2.636219278429053e-06

Goldfeld-Quandt Test: F-statistic=1.9995164818409268, p-value=0.0007090877682898954

<img width="679" alt="Screen Shot 2023-11-10 at 7 07 25 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/e890db2f-37fb-48bf-a01e-f45a02504cee">
<img width="678" alt="Screen Shot 2023-11-10 at 7 07 36 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/33c4f711-ee7a-440c-9682-48e9526ba585">
<img width="681" alt="Screen Shot 2023-11-10 at 7 07 45 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/6c3e03c5-2074-45af-bead-25016d2a826c">

Multiple Linear: Wine 

Rainbow Test: stat=1.893714151703762, p-value=0.001790364287723384

Shapiro-Wilk Test: W=0.9577372074127197, p-value=3.4421846066834405e-05

Goldfeld-Quandt Test: F-statistic=2.630372148018502, p-value=8.122018172258795e-06

<img width="681" alt="Screen Shot 2023-11-10 at 7 08 49 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/68120752-35d9-49d1-961c-e5e1cf6a3a12">

<img width="859" alt="Screen Shot 2023-11-10 at 7 22 40 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/d427a04a-6e48-4813-b824-e2de4c113f40">


<img width="682" alt="Screen Shot 2023-11-10 at 7 10 08 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/244de743-07d4-49ca-b7e2-77d001378892">

