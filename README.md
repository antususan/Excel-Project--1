# Excel-Project--1
In this project I did data cleaning, data analysis, data insight, and data visualization in Excel 
>This repository contain my submission of analysis of bike buyers data using excel given by Alex the Data Analyst 
>Here is the [data set](https://1drv.ms/x/s!Ah7nRitOulIzbLh-um1eEcECq78?e=41qgcZ)

>![This is an image](https://miro.medium.com/v2/resize:fit:720/0*8GqdW0YynQv_SaY1)

>**#Goal** of the project is to find or search for a connection from any variable in the sheet that possibly leads to bike purchasing and to determine which kind of marketing suits most to each buyer.

>Start the data analysis framework

>**#Step- 1 ASK**

>The first part is mainly to define the problem domain by asking related stakeholders on the file.
 
>Question : Does variable in the sheet have a connection that leads to bike purchasing ?

>**#Step -2 PREPARE**

>This step mainly for organize, identify and understand given data.
>1. It is a third party data 
>2. It contains qualitative(nominal data) and quantitative(discrete data)
>3. This is a Long data type - data in which each row is a one-time point per subject, so each subject will have data in multiple rows.

>**#Step -3 Process**

>This step mainly clean the data and define what kind of error the data contains.After define the types of data issues, then begin with data cleaning.

>1. Make a copy from the original sheet
>2. Removed Duplicate data
>3. Replaced ambiguous data in Marital Status and Gender column 
>4. Changed the number format for currency in Income column 
>5. Add an age brackets as a new column -to define the specific range between the number using excel function IF()
>6. Repalced 10+ miles as More than 10+ in Commute Distance

>**#Step -4 Analyze**

 >This is a step to finding any insightful data from data.Based on that purposes,I had to create a pivot table to simplify the work.

 >1. Find a relation between the Gender and their income for Purchased Bike column 

 >At first sight, I can see that females with an average salary range 53,440 were not purchased a bike and with salary range of 55,774 were purchsed a bike  .
 >For males with an average salary of 56,208 were not purchased and with a salary range of 60,123 were purchsed a bike 

 > 2.Find a relation between the community Distance and Purchased Bike column 
 In this part ,I can see that customer with 0-1 miles buy more bikes and customers who lives more than 10+ miles buy less count of bikes

> 3.Find a relation between the Age Brackets Distance and Purchased Bike column 
 From this chart I understand that customers in middle age buy highet number of bike followed by old age and customers in Adolescent age buy less number of bikes

> 4.For comparing the exact age with age bracket I did another chart for Ages and  Purchased Bike column 
So I compared with the each ages with purchased bike column ,it is clear that customers with age between 31 to 54 -Middle age buy more bikes 

>**#Step -5 Share**

>I created an interactive dashboard in excel using charts ,which I created from each pivot tables by Marital status,Region and Education 

>**#Step -6 Act**

>Based on the insight received from the dashboards I can recommend the stakesholders to which kind of marketing suits most to each buyers
> My Recommendation to stakeholders

>Create interesting bike ads that focus on each region and target an average salary for both married or single female and male with bachelor's education degrees.


