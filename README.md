# Fraud-Transaction-Detection
“From numbers to needles in the haystack: Detecting fraud with data intelligence.”
In this Power BI project, I designed an interactive fraud detection dashboard analyzing over 5 million transactions across global locations. The goal was to reveal patterns, identify anomalies, and surface potential fraud through layered data storytelling.
________________________________________
💰 1.79 Billion in Motion – But Is It Safe?
The dataset captured a whopping $1.79 billion in transaction volume, flowing through various channels, times, and geographies. Despite the scale, the average velocity score sat at a modest 10.5, and the geo anomaly score at 0.50, showing generally stable transaction behaviour — but not without exceptions.
________________________________________
🌍 Global Hotspots for Transactions
Major cities like New York, London, Berlin, and Dubai emerged as transaction hotspots. These global finance centres likely serve as central nodes for both high-value legitimate transfers and potential fraud targets.
________________________________________
⏰ Strange Hours, Suspicious Moves
A striking insight emerged: the highest transaction volumes occurred during Midnight, Morning, and Night—each registering over 1.25 million transactions. This unusual concentration outside typical business hours raises problem for potentially automated or hidden activity.
In contrast, Afternoon and Evening transactions were nearly half that volume, suggesting possible misuse of less-monitored time windows.
________________________________________
📉 Geo Anomaly Score – What Happened in Jan 2024?
Over the course of the year, the geo anomaly score held steady between 192K–213K, but in January 2024, it plummeted to just 3K. This dramatic drop could signal:
•	A fraud detection system upgrade
•	A sudden decline in risky activity
•	Or a data pipeline failure — demanding further investigation
________________________________________
💳 Transaction Types – Where the Money Moves
•	Deposits made up nearly 70% of all transactions – the core of user activity.
•	Transfers followed at 20%, while Payments and Withdrawals formed a smaller but critical portion.
Given this distribution, deposit transactions deserve the highest priority in fraud monitoring frameworks.
________________________________________
🏪 Merchant Category Patterns – Consistent but Cautious
Each merchant category (Travel, Retail, Entertainment, etc.) showed remarkably even distribution in total transaction value (~$216M). While this reflects balanced activity, it also masks consistent, low-level fraud — with ~$8M flagged as fraudulent across each category.
________________________________________
💸 Payment Channels – No Outliers, But Uniform Risk
Across ACH, Cards, UPI, and Wire Transfers, all payment channels showed similar volumes (~$56M each). No single channel stood out as riskier — suggesting fraud isn't isolated to a specific method but is spread thin across all channels.
________________________________________
✅ Smart Filtering – Fraud vs. Non-Fraud
The dashboard supports advanced filtering by Fraud Status, Device Type, and Transaction Type. This allows investigators to slice into specific behaviour clusters and zoom in on suspicious patterns using real-time filters.
________________________________________
Tools Used: Power BI, DAX, Data Modelling, Interactive Filtering
Focus Areas: Fraud Analytics, Anomaly Detection, Time-Series Analysis, Dashboard UX
