# datasci_6_regression
Part 1


In this dataset we are looking at dataset titled Beans by UC Irvine. 

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


<img width="676" alt="Screen Shot 2023-11-10 at 7 08 58 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/8e3929b2-37f3-4a59-a35c-ae0b5a4416eb">

<img width="682" alt="Screen Shot 2023-11-10 at 7 09 21 PM" src="https://github.com/malh718/datasci_6_regression/assets/102617334/67cd7f88-0eae-4b95-af3a-e9236096ad5e">

