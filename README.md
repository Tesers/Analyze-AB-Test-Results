# Analyze A/B Test Results

This project was completed as part of the course requirements of **Udacity's Data Analyst Nanodegree** certification program. 

### Overview

For this project, I worked on the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users. My goal was to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The steps include different parts such as; removing duplicates, hypothesis testing via bootstrapping and regression modelling.

### Used Technology Stack

You will need to install:

- Python 3.6
- Jupyter (notebook or lab)
- Pandas
- Numpy
- Matplotlib
- Statsmodels
- Scipy

### Detail Information 
This project incudes three parts.

- **Part I - Probability:** Statistics are computed to find out the probabilities of converting regardless of page. These are used to analyze if one page or the other page led to more conversions.

- **Part II - A/B Test:** Next, hypothesis testing is conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data is bootstrapped and sampling distributions are determined for both pages. Conclusions are drawn on conversions for both pages by calculating p-values.

- **Part III - Regression:** Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel. After that, relationship between place of user and behavior of user is examined. Statistical output using logistic regression is provided to check if country has an impact on conversion.

### Supporting Materials
 Before you run this code, you should download these csv files below.
 
 - [AnalyzeABTestResults2](https://d17h27t6h515a5.cloudfront.net/topher/2017/December/5a32c9a0_analyzeabtestresults-2/analyzeabtestresults-2.zip)
 - [Countries](https://github.com/MadaAlAhmadi/-Analyze-A-B-Test-Results/blob/master/countries.csv)
