# A2Z-Business Performance/Target Project


<img width="306" height="151" alt="A2Z store picture 1" src="https://github.com/user-attachments/assets/18cea599-5e78-4ab2-ba76-4f5578313278" />

## Table of Contents
* Project Overview
* Data Source
* Tools Used
* Data Cleaning/Preparation
* Expository Data Analysis
* Data Analysis
* Business Results/Findings
* REcommendations
* Limitations


### Project Overview
A2Z Business is a Convenience Store that offers a broad selection of both non-alcoholic and alcoholic beverages for quick purchase. The management of A2Z Business company wants me to review the revenue performance across all stores. Mr. John Collins, the manager, wants to know which stores were able to meet their target for the year, which store made the highest variance (Revenue - Target) and the days profitable for sales. He desires to give some days off to the best store and provide a special salary increment for all store them met their target accordingly. 

*This analysis project aims to provide insights for the revenue and target performance of all the stores in A2Z Business LTD over the past year. By analyzing various aspect of the business dataset (customer, sale, monthly target, and product record). The management seek to identify trends, make data driven recommendations, and ga9n a deeper understanding of the company's peformance.* 

### Data source 
The dataset used for this project are Customer Record, Monthly Store Target Record, Sales Record and Product Record from A2Z Business LTD, containing information each eight stores. 

### Tools Used
- Microsoft Excel
  - Data cleaning
  - Data transformation
  - Data modelling
  - Data analysis
  - Creating dashbord & presentation)

### Data Cleaning/Preparation
*In the initial data preparation phase, we performed the following task:*
1. Data loading and inspection
2. Handling missing values
3. Data trimimg
4. Chaning datatype
5. Data transformation

### Expository Data Analysis
This involves answering busines questions from the company:
- Which stores meet their target for the year?
<img width="691" height="343" alt="Daily, Weekly, Monthly and Quarterly Dashboard" src="https://github.com/user-attachments/assets/b1123824-189d-40ba-b73f-62a02eee2829" />
 
- Which store has the highest variance (Different between total revenue and business target)
<img width="793" height="398" alt="Highest variance" src="https://github.com/user-attachments/assets/16cdfb33-a71e-4011-bb3b-e8551b8ad520" />

  
- What days, month, and quarter are each store performing their best sales?

<img width="691" height="343" alt="Daily, Weekly, Monthly and Quarterly Dashboard" src="https://github.com/user-attachments/assets/95160be7-ddd4-4493-9e26-2aa11f3a870b" />


### Data Analysis
I conducted this prodect using the PACE FRAMEWORK. In order to understand the impact of this project, I carried out an Exploratory Data Analysis for each store’s dataset, comparing their total revenue with monthly target.
Include somme interesting codes here.


https://github.com/user-attachments/assets/32a8af0d-ac6e-4145-87b2-63f3fc380170

````
=SUMIF()


````
<img width="932" height="322" alt="Analysis" src="https://github.com/user-attachments/assets/7433f682-da47-4544-a8fb-99bbc2af84af" />


### Business Results/Findings
The analysis results are summariesd as follows:
1. Out of the eight stores owned by A2Z Business LTD, four store were able to impressively exceed their targets for the year with the LEE-MYERS store making the most variance of 31.1% increase, which is the difference between the total revenue and total target. Their best revenue generated was in the first and third quarters, with Sundays, Saturdays and Wednesdays the most profitable business days.
2. Other store like Lopez, Barron Fleming, and Myer Lopez store exceeded their targets with 30%, 29.5% and 26.7% respectively
3. Base on this analysis, the manager was able to notice the Novak Store and other stores that did poorly. Novak store never met their monthly target for the whole year, with difference of -24.6%.
4. Their are a few outliers in the dataset which resulted to increase in average revenue
5. There is a possitive cofrrelation between revenue and total budget

<img width="244" height="203" alt="A2Z store picture 2" src="https://github.com/user-attachments/assets/07d17b49-1f76-421e-aa05-b0094ea8b32d" />


### REcommendations
Based on the analysis carried out, i recommend the following actions:
- A2Z Business should implement the strenth of LEE MyER store and other thrieving stores, in other stores that are struggling.
- Strategic marketing campaign should be done based on statistics and not assumptions for better store performance.
- Invest more in marketing and promoting products during peak Sales seasons to maximize sales for those stores doing poorly.
- Focus on expanding and promoting products in LEE-MYERS, LOPEX, BARRON FLEMING, and MYER LOPEZ stores
- Implement a customer segmentation strategy to target high value customers in each store. 

### Limitations
- I removed all rows with null values in the target column because they would affect the accuracy of my analysis
- During data cleaning, i noticed that there is no data entry uniformism in all stores.
- There a few outliers 
  


