# Instacart_Python
Instcart is an online grocery store that operates through an app. They have good sales historically but want to uncover more information about their sales patterns.

## OBJECTIVE
Clean and merge four data sets: orders, products, department, and customer data.

Analyze the data to answer questions from marketing and sales teams (for example, busiest time of day,highest grossing days of the week, most loyal customers, etc.).

Analyze the data to discover differences in user's ordering habits based various characteristics (such as region, income, loyalty status, etc.).

Create customer profiles based on combinations of variables and analyze how their ordering behaviors may differ (for instance: pet owners, vegetarian/vegan, etc.).

## DATA
We were provided with datasets that contained all the customer information:

- Orders
- Orders_Products_Prior
- Products
- Customers
- Departments

## FOLDERS
The basket analysis was separated into the following folders:

Project Management: Contains the Project Brief
Data: Separated into Original and Prepared Data. These contain the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. NOTE: This folder has not been included
Scripts: Contains all the Python coding involved for the entire analysis process
Analysis: Contains the Visualizations used for developing insights and presenting on the final report
Sent to client: Contains the Final Report in Excel

## TOOLS
Language: Python

Libraries: Pandas, Numpy, Seaborn, Matplotlib, and Scipy

Software: Jupyter Notebooks and Excel

## SKILLS DEMONSTRATED,
Cleaning data: removed duplicates, found and resolved missing values, addressed mixed or incorrect data types.

Merging data: selected and prepared data for merging, confirmed merge was successful, and exported final merge as a pkl file.

Exploratory analysis: explored basic descriptive statistics (max/min, quartiles, mean, standard deviation) for each variable as well as using histograms, scatterplots, and bar and line charts to explore the distributions of data.

Derived new variables: grouped data by user, order, and department to allow exploration and analysis at each level; used aggregated data to create flags about user ordering habits (such as ‘new customer’, ‘loyal customer’, etc.) and demographic info (such as ‘with babies’ or ‘pet owner’); confirmed the new data created via crosstabs and value counts.

Visualizing data: used Matplotlib and Seaborn to create histograms, line charts, pie charts, and bar charts (vertical/horizontal, stacked, and 100% stacked).

Reporting results: provided an Excel file that explained the answers to questions from sales/marketing as well as documenting the data population flow, consistency checks, data wrangling, and column derivations.

