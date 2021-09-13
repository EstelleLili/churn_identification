# churn_identification
Churn identification for Telecom

SOURCE : https://www.kaggle.com/barun2104/telecom-churn


CONTEXT
With the rapid development of telecommunication industry, the service providers are inclined more towards expansion of the subscriber base. To meet the need of surviving in the competitive environment, the retention of existing customers has become a huge challenge. It is stated that the cost of acquiring a new customer is far more than that for retaining the existing one. Therefore, it is imperative for the telecom industries to use advanced analytics to understand consumer behavior and in-turn predict the association of the customers as whether or not they will leave the company.


CONTENT
This data set contains customer level information for a telecom company. Various attributes related to the services used are recorded for each customer.


QUESTION - Prevent churn, how?
1.	Analyze if we have some indicators for churn? 
- 	Characteristics of customers who leave (in opposition of customers who stay)
- 	Can we consider it as indicators ? a bunch of them yes

2.	Can we spot potential churners (candidates)?
- 	Spot candidates (those still here with bad indicators)
- 	Improve their indicators in the sense of people who stay = actions to take = recommendations


ANALYSIS
- 5 indicators we might keep:
1.	ContractRenewal
2.	DataPlan
3.	DataUsage
4.	CustServCalls
5.	DayMins
- 2 seem to be interested :
OverageFee
MonthlyCharge


Final indicators for churn :
•	ContractRenewal
•	CustServCalls
•	DayMins
•	OverageFee
