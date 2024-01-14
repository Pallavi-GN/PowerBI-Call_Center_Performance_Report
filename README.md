# Call_Center_Performance_Report

## Introduction
The Call Center Analytics Report on Power BI offers a detailed examination of critical performance metrics to provide actionable insights for enhanced decision-making.

## Data Source
Call Center Data: The primary dataset used for this analysis "CAll CENTER DATA"(excel file).

 ## Data Preprocessing
1.Replace all null values/blank values with 0.

2.Change datatype wherever required.

3.Extract seconds, minutes from AVG. TALK DURATION and create a new column named "Duration on Calls" (change the data type).

## Data Overview
The dataset contains the following columns:
	CALLER ID, this column gives the unique identification number of each caller

	AGENT, here we have names of each agent 

	DATE, gives you the date of each call have been received/got it on that particular date

	TIME, we have time here in hh:mm:ss format of each call have been received

	TOPIC, name of the subject on calls has been received (topic names)

	ANSWERED, here we get to know whether call has been received or abounded by giving us a value in yes/no format(Y/N) 

	RESOLVED, name of the column itself says, calls which agents received it resolved or not. (Y/N)

	SPEED OF ANSWER IN SECOND, what is the speed of each call

	AVG. TALK DURATION, particular agent how long has been gone through on particular call-in average duration

	SATISFATION RATE, the rating of each agent, who has got how much rating on satisfying callers query on each call

 ## --- Below are the information/KPIs/demands to be performed in order to meet client’s requirement ---
	Calculate total number of calls

	Create a new column to calculate total number of calls answered and total number of calls been rejected

	Calculate total % of calls been answered and total % of calls been rejected

	Create a new column to calculate how many calls been resolved 

	Create a new column to calculate how many calls been not-resolved 

	Find top 1 agent who answered maximum calls

	Top 1 agent who got highest satisfaction rate

	Use a chart to display total number of calls by topic wise

	Duration on calls by every agent

	Total calls by days and months for the year 2021

	Use Slicers to interactive with other charts by month and day wise.

	Finally, give the overall 2021 performance ratings 

	Use any suitable custom chart to show(give) overall 2021 performance satisfaction rating. 

## Report Conclusion

In conclusion, the Power BI report provides a comprehensive overview of the call center's performance, including insights into call statistics, agent performance, topic trends, and customer satisfaction. The interactive features such as slicers allow users to dynamically explore the data and gain valuable insights. The report is stored on GitHub for easy access and sharing. The client can use this report to make informed decisions and improve the call center's efficiency and customer satisfaction.
