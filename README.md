# Analyze A/B Test Results

This project was completed as part of the course requirements of **Udacity's Data Analyst Nanodegree** certification program. 

### Overview

For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users. My goal was to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The steps include different parts such as; removing duplicates, hypothesis testing via bootstrapping and regression modelling.

### Used Technology

In order to run the notebook, you'll need to install:

- Python 3.6
- Jupyter (notebook or lab)
- Pandas
- Numpy
- Matplotlib
- Statsmodels
- Scipy

### Detail Information 
This project incudes three parts.

- **Part I - Probability:** Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

- **Part II - A/B Test:** Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

- **Part III - Regression:** Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel. After that, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.

### Supporting Materials
 Before you run this code, you should download these cvs files below.
 
 - [AnalyzeABTestResults2](https://d17h27t6h515a5.cloudfront.net/topher/2017/December/5a32c9a0_analyzeabtestresults-2/analyzeabtestresults-2.zip)
 - [Countries](https://github.com/MadaAlAhmadi/-Analyze-A-B-Test-Results/blob/master/countries.csv)
