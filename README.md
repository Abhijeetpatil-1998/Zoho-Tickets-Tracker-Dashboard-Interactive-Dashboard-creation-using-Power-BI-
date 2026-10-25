# Zoho-Tickets-Tracker-Dashboard-Interactive-Dashboard-creation-using-Power-BI
## Project Objective
The IT support and operations management team wants a single ticket tracking dashboard as on May 25. So that management can track open vs. closed tickets, monitor ticket escalation levels (L1, L2, L3), check ticket owner performance, and analyze client and product ticket volumes to optimize support response.
## Dataset used
- Ticket-level data up to May 25
- Fields: Ticket ID, Ticket Owner, Ticket Status, Escalation Level (L1, L2, L3), Product, Client Name, Department Name, Ticket Date / Month
-   Dataset: data/zoho_tickets_data.xlsx (add your file here)
 ## Questions (KPIs)
  - What is the total number of tickets and how many are open vs. closed?
  - How many open tickets are sitting at L1, L2, and L3 escalation levels?
  - What is the overall closure percentage vs. open percentage?
  - How is each ticket owner performing on ticket status and volume?
  - What is the ticket volume breakdown across different products by escalation level?
  - Which top 12 clients account for the highest share of total tickets?
  - How does ticket creation volume trend day-by-day throughout the month?

## Dashboard Interaction
- <a href="https://github.com/Abhijeetpatil-1998/Zoho-Tickets-Tracker-Dashboard-Interactive-Dashboard-creation-using-Power-BI-/blob/main/Zoho%20Tickets%20Tracker%20Dashbaord.jpeg">View Dashboard</a>

## Process
- Verified data for missing values, duplicate ticket logs and anomalies, and sorted out the same.
- Made sure data is consistent and clean with respect to data type, status categories, and date format.
- Built the data model and created DAX measures (Total Tickets, Open Tickets @ L1/L2/L3, Closed Tickets, % Resolution, % Grand Total Tickets).
- Created visuals according to the questions asked: Top KPI summary ribbon, ticket owner status table, product by level matrix, top 12 clients pareto bar chart, day-wise trend column chart, and status donut chart.
- Merged all visuals into one dashboard and applied slicers (Department Name, Month) to make it dynamic.
## Dashboard  
![Zoho Tickets Tracker Dashbaord](https://github.com/Abhijeetpatil-1998/Zoho-Tickets-Tracker-Dashboard-Interactive-Dashboard-creation-using-Power-BI-/blob/main/Zoho%20Tickets%20Tracker%20Dashbaord.jpeg)

## Project Insight
- Total of 1,040 tickets (1,064 total records across levels) were logged, with 1,018 tickets closed.
- 22 tickets remain open across levels (4 at L1, 8 at L2, and 10 at L3).
- Overall ticket resolution stands at 95.68% closed vs. 4.32% open.
- Gurudutt Bhakta handled the highest overall volume (1,019 tickets, 1,018 closed), while Sagar Pande has the highest pending open workload (13 open tickets).
- UPI is the top ticket-generating product with 420 tickets (399 closed, 21 open/escalated), followed by DMT (167 tickets, all closed).
- The top 2 clients account for over half of all support volume: J&K UPI at 364 tickets (35.03%) and yesmoneysor at 177 tickets (17.01%).
- Daily volume peaked toward the end of May, reaching 144 and 143 tickets/day on May 27 and 28.

## Final Conclusion
To improve resolution efficiency and streamline support operations, primary focus should be directed towards resolving high-tier escalations (10 tickets pending at L3). Support capacity should be allocated to J&K UPI and yesmoneysor, as these two accounts represent over 52% of total ticket load. Redistributing open tickets currently assigned to Sagar Pande and sharing resolution workflows from high-volume resolvers like Gurudutt Bhakta will help clear bottlenecks during peak volume days at the end of the month.

## Tools Used
- Power BI Desktop (Data model, DAX, Visuals, Slicers)
- Microsoft Excel (Data cleaning)
