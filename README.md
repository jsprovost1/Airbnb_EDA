# Three Things You Should Expect From Airbnb Superhosts
## Insights From Seattle Airbnb Dataset


### Introduction
This project investigates the main characteristics that separate regular hosts from superhosts on Airbnb. To be recognized as a superhost, a host needs to meet these criteria:

- Hosted at least 10 trips
- Maintained at least a 90% of response rate
- Received a 5-star review at least 80% of the time as long as 50% of the guests have left a review
- Successfully completed each confirmed reservation without any cancellation.


### Aim
The goal of this project is to dive in a little more on that topic and answer these following questions:

- Is there a Price Difference in Terms of the Price Paid for a Bed Between a Regular Versus a Superhost?
- Is There a Difference in the Years of Experience Between Regular versus a Superhost?
- Is There a Difference in the Type of Housing Offered by Regular versus Superhosts?

To address our questions, we performed our analysis on the Seattle Airbnb Dataset provided by **_[Kaggle](https://www.kaggle.com/airbnb/seattle)_**


### Analysis
To address the first question of whether the price per bed differs from being a regular (mean=80.83) vs. a superhost (mean=87.10), significant difference was observed (t-test=-3.31, p=0.0009).
When looking at whether the years of experience differs between the two kinds of hosts, significant difference was observed as well between the two groups (mean_years_for_regular=5.47; mean_years_for_super=5.66; t-test=-2.88, p=0.004).
Finally, a significant difference was found when comparing both groups offering a house for their trip (t-test=-2.26; p=0.024). 
Our analysis revealed that superhosts charged more for a bed, although they have greater experience and they offer a greater proportion of houses as opposed to any other types of homes.


### Conclusion
We can conclude that you will have a better chance of having a great experience if you stay with a superhost. However, it would be unwise not to consider regular hosts as most of them are trying to get their credentials up to the level of a superhost. 
In the end, becoming a superhost is a work in progress, and because of the way the platform works, hosts should try their best to offer the best experience in order to stay in business. Consequently, it is definitely plausible that you could have a wonderful experience, and for a few bucks cheaper. Who wouldn't want that?

This repository contains a README.md file as well as a jupyter notebook called Airbnb_Seattle.ipynb where you will find the code for each analysis. Also, you will find the dataset used for the analysis.
The exploratory data analysis was performed using Python 3.6.4 with the following librairies:
    
- Numpy==1.14.2
- Pandas==0.23.4
- sklearn==0.20.0
- seaborn==0.9.0
- matplotlib==2.2.2
- scipy==1.0.0
- statsmodels==0.9.0
