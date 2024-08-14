# Hotels-Revenue-Analysis---Power-BI
Problem Statement
Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Task:
Clean the Data , Prepare the data model .
Create All Relevant KPI such as ADR ,Revpar , DSRN , DURN , DBRN and others 
Provide the insights or area of improvement to improve the revenue.

DataSet OverView:
dim_date – This table contains dates, week numbers, and day type (weekend and weekday)
dim_hotels – This table contains data like property id, property name, category, and cities
dim_rooms – This table includes room_id and room class
fact_aggregated_bookings – This is a fact tale that contains property id, check-in date, room category, successful bookings, and capacity

Data Model :

![image](https://github.com/user-attachments/assets/63460ee1-88d4-433d-a5e0-86ce4d331243)

Dashboaard Overview :

![image](https://github.com/user-attachments/assets/f99799ca-1be0-45c7-b7d8-18f39d829090)

Will be showcasing the revenue and KPI Analysis over  team period , on the basis of city and booking plaatofrm .
Filters Provided : Weekly Tiles , Monthly FIlter , City Filter , Week Type Filter , Platform Filter , Property Filter .

Overall KPI 
Total Revenue Collected 1.71 Billion 
Revpar - 73472
ADR- 12696 
Realisation Rate -70% 
Occupancy - 57.9%
DSRN - 2528 

City Insights :

![image](https://github.com/user-attachments/assets/459f011c-45a0-44b0-a16b-403b8d0197a8)

![image](https://github.com/user-attachments/assets/6aa63885-fdbb-4ad0-9ab2-72221e39743c)

![image](https://github.com/user-attachments/assets/246e44a8-99d0-4d60-8f22-df77d0181983)

![image](https://github.com/user-attachments/assets/231b3476-bcde-4cab-a395-2eacc6cfa70d)


 Mumbai is the Highest Revenue Generating City , generating 0.66 billion of revenue and also  has the highest Revpar (8906) , Highest ADR (15386)  and also has the Realization of 70.22 % 

Delhi has  the Highest Occupancy of 60.55%  and also got the highest avg rating of 3.78

Delhi has slightly highest cancellation rate compared to  others 

Hyderabad has the lowest ADR and Revpar 



Booking Platform Analysis :

![image](https://github.com/user-attachments/assets/f92c8ca5-fb16-487c-9446-f1d3dd97d1a0)

Will be analysing the platform used more often to book hotel which generate more revenue , which has more Occupancy & cancellation rate and how much ADR each platform is generating .


Total Revenue By Platform :

![image](https://github.com/user-attachments/assets/651f8a77-08ca-4724-92e6-48b31bfe821e)

![image](https://github.com/user-attachments/assets/8d31db61-d076-4172-b5a6-2b744398e307)

![image](https://github.com/user-attachments/assets/6d195c88-2e47-479c-8621-aadbde80948e)

![image](https://github.com/user-attachments/assets/d6f808d6-ff26-4ab1-b54e-e8d71ba012e1)

We got the maximum booking(55k) , cancellation(14K) and revenue(699M) from other platforms and our DBRN , DURN and Revpar is also the highest from Other platforms 

Maximum ADR is from Direct Offline Mode of booking and lowest from Direct Online Booking 

Make your trip and logtrip are the platforms which generate the good revenue after other platforms and ADR is also good from these platforms  

One thing to notice is Offline Mode of booking is the one which has the lowest bookings, Revenue  , lowest ADR, Revpar , DBRN & DURN

We got the maximum bookings in mumbai and Hyederbad  and on the other hand  our business is very low in delhi & abnglore Even though the ADR of both the states is not even  low .


Room Class Analysis 


![image](https://github.com/user-attachments/assets/8b2ba4ad-c011-454f-b667-ebb0d64803dc)

This Reveals one important thing that hotels have less booking on hotel , more adr & occupancy and that is because capacity is less on weekends .

![image](https://github.com/user-attachments/assets/b6e38259-257a-4781-83a6-3b6407ccd728)


Room Class Elite has generated the highest revenue  and also has the highest no shows with the average rating of 3.6  , highest DSRN
Presidential  Room Class has the lowest no shows , Highest ADR & Revpar 


Properties Analysis 

![image](https://github.com/user-attachments/assets/d3964a6a-2240-4293-8511-6b368444a6d0)

![image](https://github.com/user-attachments/assets/017c1733-2206-4b51-a262-1e3e7f2d0fb2)

![image](https://github.com/user-attachments/assets/22d79d86-f092-4aa9-8fa3-f0878ac9b425)


Atliq Exotica has generated the highest revenue and we need to focus on Atliq Season hotel it has the highest  ADR and lowest Avg rating , Lowest DSRN 
Atliq Blu had the highest Average Rating and was 72.54% higher than Atliq Seasons, which had the lowest Average Rating at 2.29.
13.59% of revenue realized from Mumbai. 
Revapar is almost same in all the properties 
We also need to focus on Atliq Grands has the second lowest rating & Revenue & Occupany 


KPI ANALYSIS Over Time periods ( weekly , monthly & Daily ) 


![image](https://github.com/user-attachments/assets/d3829c65-ff06-4378-bd2c-3223d69ee565)

![image](https://github.com/user-attachments/assets/0a0bafa3-89f1-428c-93ef-689d7a0ae8da)

![image](https://github.com/user-attachments/assets/bc6fde85-662b-4034-ac13-478749379944)


Monthly ADR , Occupancy , Revpar 

![image](https://github.com/user-attachments/assets/747f8d49-e28f-4372-89fd-6f9ddc7552cc)

![image](https://github.com/user-attachments/assets/a3fb3e4b-c461-44c1-96f4-18f7541fa05c)


![image](https://github.com/user-attachments/assets/83be0947-e76b-4745-9abc-ada666da78f5)


June month has seen the dip in revenue , even the ADR and Occupancy is low 
July month has shown the significant improvement in ADR  and Occupancy and revenue is also back to normal business 



