# Instacart_Python

## BACKGROUND
Performing a data analysis project utilizing Python to examine data from an existing online grocery store, Instacart.

## INTRODUCTION
Instacart, an online grocery store that operates through an app, already has very good sales, but they want to uncover more information about their sales patterns.

## OBJECTIVE
Perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria.

● The sales team needs to know what the busiest days of the week and hours of the day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders.
● They also want to know whether there are particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times.
● Instacart has a lot of products with different price tags. Marketing and sales want to use simpler price range groupings to help direct their efforts.
● Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
● The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviors differ. For example:
  ○ What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?
  ○ Are there differences in ordering habits based on a customer’s loyalty status?
  ○ Are there differences in ordering habits based on a customer’s region?
  ○ Is there a connection between age and family status in terms of ordering habits?
  ○ What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
  ○ What differences can you find in ordering habits of different customer profiles? Consider the price of orders, the frequency of orders, the products customers are ordering, and anything else you can think of.

- Clean and merge four data sets: orders, products, department, and customer data.
- Analyze the data to answer questions from marketing and sales teams (for example, busiest time of day,highest grossing days of the week, most loyal customers, etc.).
- Analyze the data to discover differences in user's ordering habits based various characteristics (such as region, income, loyalty status, etc.).
- Create customer profiles based on combinations of variables and analyze how their ordering behaviors may differ (for instance: pet owners, vegetarian/vegan, etc.).

## DATA
Throughout this Achievement, you’ll be using a number of open-source data sets from Instacart. You’ll also receive a customer data set (created and included for the purpose of this project), on which you’ll apply what you’ve learned to address the project’s key questions. While each data set contains a different kind of information, they all include some kind of common identifier.

- Orders
- Orders_Products_Prior
- Products
- Customers
- Departments

- Data Dictionary


## FOLDERS
The basket analysis was separated into the following folders:

- Project Management: Contains the Project Brief
- Data: Separated into Original and Prepared Data. These contain the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. NOTE: This folder has not been included
- Scripts: Contains all the Python coding involved for the entire analysis process
- Analysis: Contains the Visualizations used for developing insights and presenting on the final report
- Sent to client: Contains the Final Report in Excel

## TOOLS
- Language: Python
- Libraries: Pandas, Numpy, Seaborn, Matplotlib, Scipy
- Software: Jupyter Notebooks, Excel


## SKILLS DEMONSTRATED
- Cleaning data: removed duplicates, found and resolved missing values, addressed mixed or incorrect data types.
- Merging data: selected and prepared data for merging, confirmed merge was successful, and exported final merge as a pkl file.
- Exploratory analysis: explored basic descriptive statistics (max/min, quartiles, mean, standard deviation) for each variable as well as using histograms, scatterplots, and bar and line charts to explore the distributions of data.
- Derived new variables: grouped data by user, order, and department to allow exploration and analysis at each level; used aggregated data to create flags about user ordering habits (such as ‘new customer’, ‘loyal customer’, etc.) and demographic info (such as ‘with babies’ or ‘pet owner’); confirmed the new data created via crosstabs and value counts.
- Visualizing data: used Matplotlib and Seaborn to create histograms, line charts, pie charts, and bar charts (vertical/horizontal, stacked, and 100% stacked).
- Reporting results: provided an Excel file that explained the answers to questions from sales/marketing as well as documenting the data population flow, consistency checks, data wrangling, and column derivations.
