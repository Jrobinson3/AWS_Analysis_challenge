# AWS_Analysis_challenge
Upload the following to AWS_Analysis_challenge GitHub repository:
1. Amazon_Reviews_ETL.ipynb file.
2. Vine_Review_Analysis.ipynb or Vine_Review_Analysis.sql file.
3. An updated README.md that has your written analysis.

## Deliverable 1: Perform ETL on Amazon Product Reviews
With Amazon RDS, pyspark, and Postgresql, created following codes, see Amazon_Reviews_ETL.ipynb,
See four tables:
1. customers table:
![image](https://github.com/Jrobinson3/AWS_Analysis_challenge/blob/main/customers_table.png)

2. produects table:
![image](https://github.com/Jrobinson3/AWS_Analysis_challenge/blob/main/products_table.png)

review_id table:
![image](https://github.com/Jrobinson3/AWS_Analysis_challenge/blob/main/review_id_table.png)

vine table:
![image](https://github.com/Jrobinson3/AWS_Analysis_challenge/blob/main/vine_table.png)

## Deliverable 2: Determine Bias of Vine Reviews	
Using PySpark, determined if there is any bias towards reviews that were written as part of the Vine program. For this analysis, identified if having a paid Vine review makes a difference in the percentage of 5-star reviews.
See Amazon_Reviews_ETL.ipynb.

## Deliverable 3: A Written Report on the Analysis	
For this part of the Challenge, write a report that summarizes the analysis that performed in Deliverable 2 above.
The report contains the following:
1. Overview of the analysis: Explain the purpose of this analysis.
-The purpose of this analysis is to identify any bias toward favorable reviews from Vine members in  music instrument dataset. This will help the SellBy stakeholders and management what to do in the future. 
	
2. Results: Using bulleted lists and images of DataFrames as support, address the following questions:
How many Vine reviews and non-Vine reviews were there?

-Total review count was 904,765. Count of piad reviews which are filted for 50% of the reivews were helpful were 60 and count of the nopaid reviews which are filted for 50% of the reviews were helpful were 14,477.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

-Paid(Vine) reviews for 5-star rating were 34 out of 60 and non-vine reviews for 5-sstar rating were 8212 of of 14,477. 

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

-56.67% of vine reivews were 5 stars and 56.72% of non-vine reviews were 5 stars. 

3. State if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

-In this anlysis, there is no bias for reviews in the vine program since the percentage of the 5-star rating in vine reviews was less than the 5 stars of the non-vine reviews.  In the result, the people provide the review does not biased whether they paid or not. 
Additionally, percentage of helpful votes in paid review was much less than percentage of helpful votes in nonpaid reviews. 
Therefore, there is no bias for the reviews in the vine program. 


