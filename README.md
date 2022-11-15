# [Automating Credit Approval](https://github.com/Natashyatiro/Automating-Credit-Approval)
* Created a tool that predict loan amount and customer’s default based on customer’s age and income to help bank in automating their credit approval process.
*	Optimized and compared Linear Regression, Decision Tree, Random Forest, GBoost, MLP Regressor, CNN, Random Forest Regressor Optimization to predict loan amount and to reach the best model using Python and Orange.
*	Optimized and compared Logistic Regression, Decision Tree, Random Forest, GBoost, MLP Classifier, CNN (Keras Sequential) with Keras Tuner to predict loan amount and to reach the best model using Python and Orange.
*	The best model performance is by Regressor Optimization for Random Forest with 2456.62 RMSE in loan amount prediction, and Gradient Boosting with 85.88% accuracy in default prediction.
* Built a client facing API using flask which can be accessed in this [Application Page](https://credit-approval-natashya.herokuapp.com).

![](/images/vis1.png)
![](/images/vis2.png)

![](/images/resul2.png)

# [Casting Product Image Classification to Detect Defective Products](https://github.com/Natashyatiro/Casting-Product-Image-Classification)
*	Created a tool that can classify defect and non-defective casting product based on product images.
*	Built and compared Logistic Regression, Tree, Gradient Boosting, Random Forest, Neural Network model using different embedders (Inception V3, VGG-16, VGG-19) in Orange.
*	The best model for this case is logistic regression or neural network with Inception V3 embedders that result in 99.7% of accuracy.

![](/images/orange.png)

![](/images/result_orange.png)

# [Fetal Heart Health Condition Classification in R](https://github.com/Natashyatiro/Fetal-Heart-Health-Condition-Classification-)
*	Created a tool that classifies fetal heart health conditions (normal, suspicious, pathologic) based on cardiotocography data.
*	Optimized and compared e Logistic Regression for Multicategory Y, CART, and Random Forest in R to reach the best model.
* Random Forest performed best out of three with highest accuracy (99.6%) with both a low specificity and a low fall-out value. Not to mention, Random Forest in this study also outperformed models from previous research.

![](/images/result_r.png)

# [Querying Global Warming Datasets using SQL](https://github.com/Natashyatiro/Querying-Global-Warming-Datasets-using-SQL)
* Created SQL Scripts to generate queries from 5 datasets regarding global warming using MySQL.
* Queries Examples:

Display a list of [country_or_area], [year], [category], and average emission [value] when the [country_or_area]’s emission [value] of the [year] is less than the average emission [value] of the [country_or_area].
![](/images/sql1.png)

For each year (2008 to 2017), display the average [value] of temperature change in “United States of America”, the year’s average [extent] of [seaice.extent] sea ice, and the corresponding average [value] of [temperaturechangebycountry.elevation_change_unc] glacier elevation change surveyed by “Martina Barandun Robert McNabb” in the same year.

![](/images/sql2.png)


# [Querying Global Warming Datasets using noSQL](https://github.com/Natashyatiro/Querying-Global-Warming-Datasets-in-noSQL)
* Created noSQL Scripts to generate queries from 5 datasets regarding global warming using MongoDB.
* Queries Examples:

Display a list of glaciers {name}, {investigator}, and amount of surveyed on the glacier done by the investigator, when the investigator has conducted more than 11 surveys on the glacier. Sort the output in alphabetic order of {name}.
![](/images/nosql1.png)

For each year (2010 to 2014), display a list of {area}, {year}, average {value} of temperature change of the ASEAN countries. Include the overall average of temperature change of all the ASEAN countries of each year.

![](/images/nosql2.png)

# [Climate Change Dashboard in Tableau](https://github.com/Natashyatiro/Climate-Change-Dashboard-in-Tableau)
*	Cleaned, joined, and aggregated 4 datasets using Tableau Prep.
*	Visualized the data from combined datasets to find patterns and get meaningful insights.
*	Forecasted and visualized CO2 emissions to 2050.
*	Built interactive dashboard using Tableau. You can access through tableau public in this [link](https://public.tableau.com/views/WhoisResponsibleforClimateChange/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).
![](/images/Group%205%20Tableau%20Vfinal-1.jpg)
