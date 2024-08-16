
#Atliq Hotel Revenue Analysis 




- **Company Overview**:
  - Atliq Grands owns multiple five-star hotels across India.
  - They have been in the hospitality industry for the past 20 years.

- **Current Challenges**:
  - Facing declining market share and revenue in the luxury/business hotels category.
  - Issues attributed to strategic moves from competitors and ineffective decision-making in management.

- **Strategic Initiative**:
  - The Managing Director has proposed incorporating "Business and Data Intelligence" to regain market share and revenue.
  - Lack of an in-house data analytics team to provide necessary insights.
- **Tasks**:
  - Clean the data and prepare the data model.
  - Create all relevant KPIs, such as:
    - ADR (Average Daily Rate)
    - RevPAR (Revenue Per Available Room)
    - DSRN (Daily Sales Revenue Net)
    - DURN (Daily Utilization Rate Net)
    - DBRN (Daily Booking Revenue Net)
    - Other relevant KPIs
  - Provide insights or areas of improvement to enhance revenue.

# **Dataset Overview** 
  - **dim_date**: Contains information about dates, including:
    - Dates
    - Week numbers
    - Day type (weekend or weekday)
  
  - **dim_hotels**: Provides details about the hotels, including:
    - Property ID
    - Property name
    - Category
    - Cities

  - **dim_rooms**: Contains data about room types, including:
    - Room ID
    - Room class

  - **fact_aggregated_bookings**: A fact table that includes:
    - Property ID
    - Check-in date
    - Room category
    - Successful bookings
    - Capacity


## Data Model 

![App Screenshot](https://i.imgur.com/HFpICVV.png)



##  ![Icon](https://img.icons8.com/ios-filled/50/000000/dashboard.png) Dashboard Overview 

- **Home Page**: 
![App Screenshot](https://i.imgur.com/C9bWNl6.png)
Overview and access to different reports.
- Overall KPI 
    - Total Revenue Collected 1.71 Billion 
    - Revpar - 73472 
    - ADR- 12696 
    - Realisation Rate -70% 
    - Occupancy - 57.9% 
    - DSRN - 2528

# Revenue Analysis Report
![App Screenshot](https://i.imgur.com/kVlH2vY.png)
    **Detailed analysis of revenue trends and metrics.** 
- Mumbai is the Highest Revenue Generating City , generating 0.66 billion of revenue and also has the highest Revpar (8906) , Highest ADR (15386) and also has the Realization of 70.22 %.
- Delhi has the Highest Occupancy of 60.55% and also got the highest avg rating of 3.78.
- Delhi has slightly highest cancellation rate compared to others
- Hyderabad has the lowest ADR and Revpar













# Booking Platform Analysis Report 
![App Screenshot](https://i.imgur.com/bvuiBFL.png)Examination of booking patterns and statistics.
  - **Revenue Generation**:
    - **Other Platforms**:
      - **Maximum Bookings**: 55,000
      - **Maximum Cancellations**: 14,000
      - **Maximum Revenue**: $699 million
      - **Highest Metrics**: DBRN (Daily Booking Revenue Net), DURN (Daily Utilization Rate Net), RevPAR (Revenue Per Available Room)
    - **Direct Offline Booking**:
      - **Maximum ADR** (Average Daily Rate)
    - **Direct Online Booking**:
      - **Lowest ADR**

  - **Other Notable Platforms**:
    - **MakeMyTrip** and **LogTrip**:
      - Generate good revenue.
      - Good ADR (Average Daily Rate).

  - **Offline Mode of Booking**:
    - **Lowest Metrics**:
      - Bookings
      - Revenue
      - ADR
      - RevPAR
      - DBRN
      - DURN

- **Geographical Performance**:
  - **Highest Bookings**: Mumbai and Hyderabad.
  - **Lowest Business**: Delhi and Bangalore.
    - Despite the low business, ADR in Delhi and Bangalore is not the lowest.

# KPI Analysis 
  - **Monthly & City Level KPI Analysis**: 
  ![App Screenshot](https://i.imgur.com/rBdBKKP.png)
Analysis of KPIs on a monthly basis and by city.
  - **Weekly Level KPI Analysis**: 
  ![App Screenshot](https://i.imgur.com/h7jAH52.png)
  Examination of KPIs on a weekly basis.

  KPI Analysis Over Time Reveals Cancellation % and Realisation % rate is almost same in all weeks  ,  it changes limiting to 1% up and down .
# Properties Analysis
![App Screenshot](https://i.imgur.com/6sPGBQw.png)

  - **KPI Analysis of Properties , city wise ,**:
![App Screenshot](https://i.imgur.com/dnYla7G.png)
 Performance analysis of different properties based on KPIs.

- **Revenue and Performance Highlights**:
  - **Atliq Exotica**:
    - **Generated the Highest Revenue**.

  - **Atliq Season**:
    - **Highest ADR (Average Daily Rate)**.
    - **Lowest Average Rating**.
    - **Lowest DSRN (Daily Sales Revenue Net)**.

  - **Atliq Blu**:
    - **Highest Average Rating**.
    - **72.54% Higher Rating** compared to Atliq Season.
    - **Atliq Season** had the lowest average rating at **2.29**.

  - **Revenue by Location**:
    - **Mumbai**: Contributed **13.59%** of the total revenue.

  - **RevPAR (Revenue Per Available Room)**:
    - **Similar Across All Properties**.

  - **Atliq Grands**:
    - **Second Lowest** in:
      - Rating
      - Revenue
      - Occupancy


# **Analysis of Room Category**: 
![App Screenshot](https://i.imgur.com/nGGAkpG.png)
Insights and trends related to different room categories.

- **Room Class Performance**:
  - **Elite Room Class**:
    - **Highest Revenue**.
    - **Highest No-Shows**.
    - **Average Rating**: 3.6.
    - **Highest DSRN (Daily Sales Revenue Net)**.

  - **Presidential Room Class**:
    - **Lowest No-Shows
