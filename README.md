 # Text as data for idiosyncratic price changes
 
 Firm level price data has been made available by the Bureau of Labor Statistics (BLS) 
 starting in the late 1970's. However, data from newspapers that advertise firm's price 
 changes (i.e., sales) are publicly available from the late 1800s. In macroeconomic 
 theory, firm sales (temporary price changes) have implications for both monetary policy 
 and inflation. The purpose of this mini-project is to make use of a novel dataset, 
 consisting of the text of advertisements appearing in the New York Times from 1850-2010. 
 Each record has a binary variable indicating if the advertisement was for a sale 
 (sale = 1) or not (sale = 0). 
 
 We aim to answer two questions:
 
 Question 1: Can the text from advertisements be used to predict whether a price change 
 occurred (i.e., a sale)?
 Question 2: Can the text from advertisements be used to easily categorize a product? 
 This is needed since data from the BLS is based on different industries/categories, 
 and for sale data to be useful, product category would be necessary.
 
 Note that due to the confidential nature of the full dataset, only a subsample is 
 included. A Jupyter notebook provides a summary of the mini-project using the full
 dataset. 
 
+   Author: Michael Munsell
+   Date: February 20, 2018
+   Code: Python 3.6.1, pandas, numpy, sklearn