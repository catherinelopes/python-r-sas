This folder contains data science tutorials in Python, R and SAS, and seeks to help those interested in learning a new data science programming language by demonstrating basic data science tasks, as well as some machine learning algorithms.  To the extent possible, all three tutorials follow the same progression and can be compared by example number.  The tutorials also include extensive helpful links to the documentation for the programming languages.  

The tutorials were produced using R Markdown knitr in order that the examples and results might be reproducible.  All data used in these examples is included in this folder as well.  Please be advised before running the code in the tutorials that the file paths for the data must be changed to reflect your environment.  Also, Python 3.5.2, R 3.3.1, SAS 14.2 (SAS/STAT 14.2, SAS/ETS 14.2, SAS/OR 14.2, SAS/IML 14.2, SAS/QC 14.2), and SAS Enterprise Miner Workstation 14.2 were used to generate these results, so if you have different versions it is possible the results are differenct.  Finally, there are several Python & R packages that need to be installed in order to go through the tutorial successfully.

Python: pandas (0.20.2), NumPy(1.12.1), Matplotlib.PyPlot, seaborn(0.7.1), re(2.2.1), decimal(1.70), sklearn(0.18.2), statsmodels.api, xgboost(0.6), pyclustering, PyFlux(0.4.15)

--- I used pip install ____ or conda install ____ where appropriate.

R: gdata, rjson, ggplot2, dplyr, tree, randomForest, gbm, xgboost, e1071, RSNNS, caret, kernlab, dbscan, forecast

--- I used install.packages("name_of_package")

In order to run the SAS tutorial successfully, you will need Base SAS, SAS Enterprise Miner, and access within SAS to call R in order to execute R code.  For more information on calling R code within SAS please see [this post](https://communities.sas.com/t5/General-SAS-Programming/Run-R-code-inside-SAS-easily/td-p/210116).

Happy programming and analyzing!
