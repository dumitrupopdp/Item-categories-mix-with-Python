# Item-categories-mix-with-Python

The concept was to try and see what mix of item categories is needed for a certain amount of profit if there is a limit of capital required for investment.

For this project, I’ve used a CSV file for the original data, Python for preparing the data, and Power BI to visualize the data from Python.

The prediction is based on sales transaction data from a CSV file. The data can be found in the "Sales.csv" file.

I’ve imported the data in Python using Pandas. After that, I cleaned the data and prepared it for the prediction phase. Using “train_test_split” and “LinearRegression“ from the Sklearn library I’ve separated the data into training and testing sets and run the prediction using those sets of data. From here I’ve set up coefficients for each item category, which were used in Power BI to create an interactive dashboard. The code can be seen in the "Item categories mix for target profit.ipynb” file.

In Power BI I imported the CSV file and applied the Python script to that data. There are 3 categories of visualizations (“Coefficients”, “Investment”, “Outcome”). The “Coefficients” category is used to display the item category coefficients obtain with the Python script. The “Investment” group of parameters is used to take input from the user regarding the amount wanted to be invested in each item category. In the “Outcome” group, there are 2 visualizations that show the profit amount predicted and the percentage of return on capital invested. This can be seen in the "Item categories mix with Python.pbix" file.
