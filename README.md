# Quality-Assessment-project   
![image](https://github.com/Arash-Kamboj/Quality-Assessment-project/assets/156613048/4faf5a17-f194-40ea-b66a-68cd40ab4fe4)

------------------------------------------------------------------------------------------------------------------------
This project is regarding a giant beverage company. Being a quality analyst, my primary object is to assess the production lines and keep them in check over the time to meet the industrial standards. The organisation keeps track of every move of the production lines for instance, the timings, quantity of beverages, etc. 
I am tasked with checking if different production lines are pouring the right amount of beverages with proper carbonation in a predefined time. 

-------------------------------------------------------------------------------------------------------------------------
Objective: To explore the assessment data and provide relevant insights. By transforming these insights into practical strategies, the company can make significant strides in improving the assembly lines and therefore the production.

Problem statement: To reiterate, the company aims to optimise the workings of production lines. To accomplish this goal, I need to understand extremes, patterns and associations with applications of probability and distributions.

--------------------------------------------------------------------------------------------------------------------------
**Data collection: Understanding the data**

![image](https://github.com/Arash-Kamboj/Quality-Assessment-project/assets/156613048/5f649b00-3f6d-4cf1-8439-9eb249318aa1)

1. Id: Product Id (this is system generated while collecting sample)
2. Assembly line: There are 2 different assembly lines A and B used for production of beverages.
3. Quantity (lts.): The amount of beverage filled in the bottle.
4. CO2 dissolved: Amount of CO2 for carbonation in gms.
5. Time limit Crossed: If the time limit has crossed to process the bottle (fill & packaging).
---------------------------------------------------------------------------------------------------------------------------
**Data processing: Cleaning the data**

![image](https://github.com/Arash-Kamboj/Quality-Assessment-project/assets/156613048/56f903e9-0e2f-4ead-87c0-87f30a5fa371)

1. Standardise the Assembly Line column: Make the column consistent so that it has cardinality of 2. 
2. Remove any empty or incomplete rows: Check if there are any rows with missing data. Substitute these values with the mean of numerical or mode for non-numerical data with respect to individual assembly lines.
3. Check for Outliers: Check for outliers in the dataset and does it make logical sense to keep them or should we treat them?

