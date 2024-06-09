#  Insights From Supply Chain In FMCG Domain

__Dashboard link__:
<iframe title="Supply Chain Insights in FMCG Domain" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiMjc5MGY2NjMtZTU0YS00N2JjLWJlNmMtOTI5MDVlYmU0MzlkIiwidCI6IjUxNjk4MzNiLWUxZWItNDlkNC1iODBiLWM0MTNjOTMxMWZkYSJ9" frameborder="0" allowFullScreen="true"></iframe>

# Problem  Statement 
Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.
   

#  Task
Peter Pandey is the data analyst in the supply chain team who joined AtliQ Mart recently. He has been briefed about the the task in the stakeholder business review meeting. Now imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following task:

1.Create the metrics according to the metrics list.   
2.Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.  
3.Create relevant insights not provided in the metric list/stakeholder meeting.  

# Data Source   
The data was provided by Codebasics as part of Codebasicsresumechallenge.These files consists of required details about customers,products and order details.    
    1. dim_customers   
    2. dim_date  
    3. dim_products   
    4. dim_targets_orders   
    5. fact_order_lines  
    6. fact_orders_aggregate


## Data Model 
![Screenshot 2024-06-06 223908](https://github.com/DenisM03/SUPPLY__CHAIN__PERFORMANCE__DASHBOARD-/assets/163861750/6317d1ab-0d0d-4854-80c8-83f8e7680c96)

## Analytical Dashboard   
![Untitled](https://github.com/DenisM03/ATLIQ__MART__SUPPLY__CHAIN__ANALYSIS/assets/163861750/3e53eb17-62a6-458d-9cfb-fc2c0d7b99c3)


## Tools Used   
Excel,PowerBi 

## Business  Terminologies
   
1.LIFR%   -  Line Fill Rate   
2.VOFR%   -  Volume Fill Rate  
3.OT%     -  On Time Delivery %   
4.IF%     -  In Full Delivery %     
5.OTIF%   -  On Time In Full %

## Content   
1.Process       
2.KPI's     
3.Insights    

## 1.Process    
The data files are transformed into power Bi desktop using power query.A data model was built by connecting the necessary fields
for analysis.Using DAX and measures  metric values were calaculated. Based on requirements measures are built that support the analysis.Tables and charts were created for visualization.A dashboard was created, that showcases the performance and analytics of the data.   

## 2. Key Metrics  

1.Total Order Lines    
2.Total Orders        
3.LIFR%   
4.VOFR%   
5.OT%       
6.IF%         
7.OTIF%     
8.On Time Target    
9.In Full Target    
10.On Time In Full Target

## 3.Insights      
✳️ There was a  significant difference in OT%,IF%,OTIF% compared to   their target.         
✳️ Overall average delay days was 2 days,average delay per customer  was 1.69 days.             
✳️ Vijay stores,Propel Mart,Rel Fresh,Lotus Mart and Acclaimed Stores have higher order quantity and higher average delay days along with Coolblue and Expression Stores. 
   This may be due to shortage of stock.   
✳️ Vadodara city has least OT%,IF%,OTIF%,LIFR% and OTIF%.               
✳️ Dairy products has highest orders i.e 38K orders with 10.56M of total order quantity also Dairy products has higher average delay days of 1.69 days in product category.           
✳️ AM Milk,AM Curd,AM Butter and AM Ghee,These are the products with highest delay days  per deliver quantity.              
✳️ OT%,IF% and OTIF% was higher in the months of  March,May and August relative to other months.              
✳️ There is no improvement in  any of the Metrics.            
