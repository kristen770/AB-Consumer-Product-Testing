# Case-Study-2-North-Wind-Distribution-Data 
## North Wind - Hypothesis Testing  
### By Kristen Davis

<p align="center">
  <img width="300" height="300" src="outback.jpg">
</p>
 
### Project Overview 
This is a 24 case study on Hypothesis Testing given mid Statistics Module (Module 2) at the Flatiron School. 

### Business Senario 
You are a DS working for Northwind, a supplier company. Your job is find interesting relationships in their database.  

### Data 
For this case study I used the northWind.sqlite data set. This included tables on Products, Orders, Employees, and Customers.  

### Methods 
This case study used statistical A/B testing, ttest, pvalue, and power anaylsis methods to examine a given hypothesis.

### Question 1: there a difference in quantity of products sold by discount rate?  
For this question I want to look at one specific product sold by one distributor to a deliverable insight recommendation on how that producer should price their product. After some general exploration I decided to focus on Outback Lager sold at 15$ unit price by Pavlova, Ltd.  

### Investigation on Quantity Sold by Discount Percentage 
I conducted Welch's Ttest, Bootstrapping and calcualted pvales for the quantity sold of this product at to 0.00% discount rate, the 0.33% discount rate, the 1.33% discount rate and the 1.67% discount rate. 

For each experiments I falied to reject the null hypothesis. 

### Conclusion 
I failed to reject the null hypothesis at 0.00, 0.33, 1.33, and 1.67 % discount rate. This leads me to believe there is little correlation between discount rate and quantity sold I turn I would provide the recommendation that Pavlov, Ltd should stop discounting their Outback Lager as it does not lead to higher sales. 

# Future Work
Given addional time I would pursue the following: 
1. Apply this analysis to other beers with in the data set- what beer do show an increase in sales given a discount? 
2. Examine what factors led the supplier changed the price of this been from 15$ to 12$. 
3. Analyze sale by region- does a particular group of customers buy at the discounted rate? 
