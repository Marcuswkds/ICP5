# ICP5

In Class Programming for Regression techniques and Data Analysis.

Marcus Wong Ken Ji

2/19/2021

Description of ICP: Learning and implementing regression techniques such as Linear and Multiple regression, plotting scatter graphs, analysing graph data, and determining any outliers.

# Question 1 Code.

![image](https://user-images.githubusercontent.com/72952948/108586094-e21b2480-7311-11eb-9b01-f9675a913151.png)

I begin by importing the appropriate modules and reading the train.csv file. I chose to use the Z-score in order to indentify the outliers for the dataset. I determined that the threshold for the z-score is 3 and plotted the data using the values of z < 3. I plotted two graphs of Garage Area vs Sale Price with and displayed both of the graphs. The first graphs shows the plot with the outliers and the second graph shows the plot without the outlier values.

Graph with outlier values.

![image](https://user-images.githubusercontent.com/72952948/108586236-b9dff580-7312-11eb-97ff-610cdb246fa8.png)

Graph with outlier values deleted.

![image](https://user-images.githubusercontent.com/72952948/108586258-e0059580-7312-11eb-92b3-ab53d7aea7f9.png)

# Question 2 Code.

![image](https://user-images.githubusercontent.com/72952948/108586296-10e5ca80-7313-11eb-8d8b-7b3a8057ea77.png)

I began by importing the appropriate modules and reading the data.csv file. Next, I converted the categorical data from the csv file into numerical data and I also removed the skewness by applying a logarithm onto the revenue and used test_split to split the data into 2 and used a test size of 0.2. With that, I calculated the R^2 score test data and the RMSE and plotted the scatter graph. 

R^2 score and RMSE for Q2.

![image](https://user-images.githubusercontent.com/72952948/108586427-1f80b180-7314-11eb-98e6-411d634d5f95.png)

Linear Regression Model for Q2.

![image](https://user-images.githubusercontent.com/72952948/108586451-4b9c3280-7314-11eb-8304-7b4d36975fdd.png)

# Question 3 Code.

![image](https://user-images.githubusercontent.com/72952948/108586585-09bfbc00-7315-11eb-8db3-77f7e10ec09a.png)

For question 3, I repeated most of the steps from question 2, but changed to find the top 5 correlated features to revenue and plotted that scatter graph instead. Compared to question 2, the R^2 value is higher but the RMSE is lower, this results in a better prediction and a model that has improved fit.

R^2 score, RMSE and Top 5 correlated features to revenue for Q3

![image](https://user-images.githubusercontent.com/72952948/108586735-efd2a900-7315-11eb-917a-191aa67b0d8e.png)

Linear Regression Model for Q3.

![image](https://user-images.githubusercontent.com/72952948/108586757-0b3db400-7316-11eb-85bf-b08d4b5c1720.png)

Video Link :https://umkc.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0c8677e3-b64b-4574-8fb2-acd50071f0d5

