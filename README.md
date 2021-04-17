# CaseStudy2DDS - Employee Attrition 

In this case study I was asked by my client DDSAnalytics to explore factors leading to employee turnover and an employee's monthly rate of pay. DDSAnalytics is a talent management company looking to leverage data science and this study is a proof of concept prior to green lighting a large study. They provided a dataset containing information on 870 employees in 36 columns, including such things as Overtime worked, Job Level, etc. in addition to mnothly income and attrition. This raw data can be found in the data folder.

Using a combination of Naive Bayes and ROC analysis I was able to determine that the top 3 factors contributing to employee attrition were Overtime, Monthly Income, and Total Years Worked. Using their variables in a Naive Bayes model resulted in an overall mean accuracy of 71% in identifying whether an employee had experienced turn over or not. I was also provided a data set without attrition labels and asked to predict whether that employee experienced attrition or not. Those results can be found in the Predictions folder.

For Monthly Income I used a combination of Linear Regression and Automatic Variable selection to find the top 3 variables contributing to an employee's monthly rate. They were Job Level, Job Role, and Total Working Years. Using these variables I was able to predict an employee's monthly income within plus or minus $986.70. I was also provided with an additional data set containing no information for employee's monthly income and was asked to predict these values using my model. Again, those results can be found in the Predicitions folder.

Additionaly, the Rmarkdown code and HTML results can be found in the Code and Analysis folder while the slides used in my presentation are located in the Presentation folder. Please see below for a link to my Youtube presentation of the results of this case study.

Youtube Presentation:
https://youtu.be/MmvPaYlUu78
