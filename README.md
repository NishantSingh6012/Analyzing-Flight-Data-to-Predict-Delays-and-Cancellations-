# About the data
The data used is collected in 2015 for the U.S. Department of Transportation Air Travel Consumer Report, encompassing more than 5,000,000 travels on commercial airlines. Each record contains information on a particular flight, such as the airline name, flight number, origin and destination airports, total distance traveled, and the scheduled and actual arrival and departure times.

<img width="700" alt="image" src="https://github.com/user-attachments/assets/829da341-fd73-4a3e-a0da-d0b77904dfde">

Source :- https://www.mavenanalytics.io/data-playground?order=-fields.numberOfRecords

# Synopsis
Problem Statement :-

We're diving into how flights performed in 2015. We want to know about things like how many flights there were, how often they were delayed, canceled, and which airlines were the most reliable. We're using a bunch of data on flights, including info on when they left, if they were canceled, and details about the airlines.

Objective:-

Through this comprehensive analysis, we aim to provide actionable insights to stakeholders in the aviation industry, including airlines, airports, and regulatory bodies, to improve operational efficiency, enhance customer satisfaction, and mitigate disruptions in flight services.

# Questions we’ll solved

* How does the overall flight volume vary by month? By day of week? 

* How many flights were canceled and its percentage?

* Primary cause of cancellation, and percentage of cancellation of each reason?

* What percentage of flights in experienced a departure delay in 2015? Among those flights, what was the average delay time, in minutes?

* Which Routes are typically the most delayed?  

* Which airlines seem to be most and least reliable?

* What are the alternate airlines that do well for the same routes?

# Data Analysis

<img width="500" alt="image" src="https://github.com/user-attachments/assets/0ce7d6a4-adb2-4895-8857-58565a3c24c2">

* Here first while doing grouping based on month, we can see that the month 7 which is July has the highest count when doing the analysis based on the month which comes down to 520718.
It can be concluded that the month of **July was the busiest of all the year**.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/c5af0e8f-a0e4-45e5-839b-43a0ed89fa6d">

* Now doing the grouping based on DAY_OF_WEEK  and plotting a bar plot and based on the count we can infer that the busiest day of the comes to be **the very first day itself**.

### How many flights were canceled and its percentage ?

<img width="440" alt="image" src="https://github.com/user-attachments/assets/a7f45a0d-03d1-444d-9349-f29c9ab44b43">

* In the dataset analyzed, there were 89,884 flights canceled, which represents approximately **1.54%** of the total flights. This indicates a notable but not overwhelming percentage of cancellations within the dataset. Factors contributing to flight cancellations could include weather conditions, mechanical issues, air traffic control delays, scheduling adjustments from airline/carrier or security.
* Understanding the reasons behind these cancellations could help airlines improve their operations and minimize disruptions for passengers.

### Primary cause of cancellation, and percentage of cancellation of each reason?

<img width="272" alt="image" src="https://github.com/user-attachments/assets/f2a873bb-e374-4812-a93a-c86a15a31474"> </br>

<img width="500" alt="image" src="https://github.com/user-attachments/assets/dcf13dca-29fb-407b-aea8-b0de58a24f4b">

* The primary causes of flight cancellations in the dataset were weather-related issues, accounting for approximately **54.35%** of all cancellations, and airline or carrier-related issues, making up around **28.11%** of cancellations. 
* National Air System issues contributed to approximately **17.52%** of cancellations, while security concerns were responsible for an extremely small percentage, just **0.02%**.
* Weather-related cancellations appear to be the most prevalent, indicating the significant impact of weather conditions on flight operations. Addressing operational strategies to mitigate the effects of adverse weather could potentially reduce the number of cancellations and improve overall airline reliability.
* Additionally, focusing on improving airline and carrier-related issues could help minimize disruptions for passengers and enhance customer satisfaction.

### What percentage of flights in experienced a departure delay? Among those flights, what was the average delay time, in minutes?

<img width="500" alt="image" src="https://github.com/user-attachments/assets/f0f818e4-f045-41ea-afb9-d6d4db009ae7">

* Based on Delayed Flights. Southwest Highest and Hawaiian lowest.

<img width="438" alt="image" src="https://github.com/user-attachments/assets/71252d16-ded3-4093-aabc-d7f3ac9d383c">

Based on Total flights. Southwest Highest and Virgin America lowest.

* BUT, Looking from from the analysis above, we cannot come to a conclusion.
  After taking into consideration the total number of flights and taking the delay as percentage we get Alaska airlines as the airline with highest delay while United Air Lines with the lowest.

In previous graph Southwest was highest because the total no, of flights of the airline was also the highest.
Therefore percentage helps us get a more clear picture.

<img width="500" alt="image" src="https://github.com/user-attachments/assets/65d98f2d-fbb2-4e3b-b918-e77e3ce64dfe">

### Which routes are typically most delayed ?
Based on the analysis of flight delay data, the following routes are typically most delayed:

1. From Bozeman Yellowstone International Airport (BZN) to Hartsfield-Jackson Atlanta International Airport (ATL) in February, with an average arrival delay of 1107.0 minutes.
2. From Valdez Airport (VEL) to Salt Lake City International Airport (SLC) in February, with an average arrival delay of 623.0 minutes.
3. From Lincoln Airport (LNK) to Hartsfield-Jackson Atlanta International Airport (ATL) in May, with an average arrival delay of 553.0 minutes.
4. From John F. Kennedy International Airport (JFK) to Daniel K. Inouye International Airport (HNL) in March, with an average arrival delay of 527.5 minutes.

* These routes experienced significantly high average arrival delays during the specified months, indicating potential issues such as weather-related disruptions, air traffic congestion, or operational challenges. Further investigation into the specific factors contributing to these delays would be necessary to address and mitigate them effectively.

### Which airline seems to be most & least reliable ?
* Most Reliable Airline: Alaska Airlines Inc. appears to be the most reliable airline, with a reliability percentage of approximately 74.27%. This indicates that the majority of their flights operate without significant delays or cancellations.
* Least Reliable Airline: United Air Lines Inc. seems to be the least reliable airline among those listed, with a reliability percentage of around 48.38%. This suggests that a significant portion of their flights experience delays or cancellations.

<img width="481" alt="image" src="https://github.com/user-attachments/assets/f75e7de7-3398-425c-bd9f-58d24bc4b555">

* Reliability percentages are calculated based on the proportion of flights that are delayed and cancelled out of the total number of flights operated by each airline. Higher reliability percentages indicate a lower incidence of delays and cancellations, while lower percentages indicate a higher incidence of disruptions.

<img width="635" alt="image" src="https://github.com/user-attachments/assets/23af5933-0bdb-4c31-a1bc-b239c22f708b">

### What are the alternate airlines that do well for the same routes ?

1. Route: LNK-ATL
   - Alternate Airline: EV
   - Total Delay: -3093 minutes
   - This indicates that flights operated by EV (ExpressJet Airlines) on the Lincoln Airport (LNK) to Hartsfield-Jackson Atlanta International Airport (ATL) route have a negative delay, suggesting that they often arrive earlier than scheduled.
2. Route: VEL-SLC
   - Alternate Airline: OO
   - Total Delay: -2911 minutes
   - Flights operated by OO (SkyWest Airlines) from Valdez Airport (VEL) to Salt Lake City International Airport (SLC) also have a negative delay, implying they frequently arrive ahead of schedule.
3. Route: JFK-HNL
   - Alternate Airline: HA
   - Total Delay: -2087 minutes
   - HA (Hawaiian Airlines) flights from John F. Kennedy International Airport (JFK) to Daniel K. Inouye International Airport (HNL) have a negative delay, indicating they are often punctual or arrive earlier than expected.
4. Route: BZN-ATL
   - Alternate Airline: DL
   - Total Delay: -1235 minutes
   - Flights operated by DL (Delta Air Lines) from Bozeman Yellowstone International Airport (BZN) to Hartsfield-Jackson Atlanta International Airport (ATL) also have a negative delay, suggesting they have a good track record of timeliness on this route.
5. Route: JFK-HNL
   - Alternate Airline: DL
   - Total Delay: -471 minutes
   - DL (Delta Air Lines) flights from JFK to HNL show a negative delay, indicating they also tend to be punctual or arrive earlier than scheduled.
* In summary, these alternate airlines demonstrate better performance in terms of timeliness on the specified routes, consistently arriving earlier than scheduled or with minimal delays compared to other carriers.

<img width="457" alt="image" src="https://github.com/user-attachments/assets/52ed4bd4-549c-49f1-9963-70bcc8c03c8d">








































