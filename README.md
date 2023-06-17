# Vardna-stores-analysis
   
#Step 1:
     Download the Vardna stores dataset from Kaggle and open it in Excel.

    First, you need to download the dataset from Kaggle. Make sure you have a Kaggle account and access to the Vardna stores dataset. Once you have downloaded the dataset, open it in Excel.

#Step 2: 
    Data Cleaning

    Check for null values:
      Inspect the dataset for any missing or null values. If you find any, decide how to handle them. You can either remove the rows with missing values or impute       them based on a suitable strategy.

    Duplicate values:
      Check for duplicate entries in the dataset. If you find any, remove them to ensure data integrity.

    Gender column:
      Look for variations in gender values, such as "W," "M," "Women," and "Men." Apply a filter to the gender column and replace "M" with "Men" and "W" with           "Women" to standardize the values.

    Qty column:
       Check for inconsistencies in the Qty column, such as a mix of numerical values (e.g., 1) and textual values (e.g., "one"). Replace any textual values with         their numerical equivalents for consistency.

#Step 3:
   Data Processing

    Age group categories:
    Create age group categories based on the relationship between gender and age. For example, you can use the following formula in a new column:
    =IF(F2>=50, "Senior", IF(F2>30, "Adult", "Teenager"))
     Adjust the column references according to your dataset structure. This formula categorizes individuals as "Senior" if their age is 50 or above, "Adult" if        their age is between 30 and 49, and "Teenager" if their age is below 30.

    Month column:
    Create a new column called "Month" to extract the month from a date column (let's assume it's column H). Use the formula:
    =TEXT(H2, "mmm")
    This formula will display the first three letters of the month. If you want the full month name, change "mmm" to "mmmm" in the formula.

    Remove formulas:
      Once you have derived the necessary columns, remove the formulas from the dataset to work with the processed data.

#Step 4:
      Data Analysis

    Perform various analyses on the dataset to gain insights. This step depends on the specific questions you want to answer or the patterns you want to identify.     Some common analyses could include:

    Examining sales trends over time (by month)
    Analyzing purchasing behavior based on gender or age group
    Identifying popular products.
    Identifying top 5 state buying their goods.


    Remember to use appropriate charts, graphs, and statistical methods to visualize and interpret the data effectively.

These steps provide a general framework for analyzing the Vardna stores dataset.


#Step 5:
      Sample Insights
            Women are most likely to buy compared to men (approx 65%)
	          Maharashtra , Karnataka and Uttar Pradesh are top 3 states (approx 32%)
	          Adults age group (30-49 yrs)  is max contributing (approx 35%)
	          Amazon,Flipkart and Mntra channels are max contributing (approx 80%)

#Step 6:
     Result:
       Final Conclusions to  improve Vrinda store sales:
	      Target **Women** customers of ** age group(30-49 yrs)** living in **Maharashtra , Karnataka and Uttar Pradesh** by showing ads/offers/coupons available            on **Amazon,Flipkart and Mntra**. 



