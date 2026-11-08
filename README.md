# Airline Delays, Cancellations and Passenger Satisfaction Analysis

An analysis of airline performance covering flight delays, cancellations, seasonal patterns, regional differences and passenger satisfaction. The goal is to find which airlines and months cause the most problems for passengers, and what the business should fix first.

Author: Sandun Lakshan Ranathunga

![Dashboard Overview](PHOTO-2026-11-08-11-52-44.jpg)

## Business Questions
- Which airlines have the longest delays?
- Which airlines cancel the most flights?
- Are delays and cancellations the same problem?
- Which months and regions are the worst for delays?
- What do passengers in each class like least?

## Key Numbers
| Measure | Value |
|---|---|
| Average delay range across airlines | 13.0 to 22.8 minutes |
| Worst cancellation rate | 12.93% (Andes Fly) |
| Best cancellation rate (named airlines) | 3.91% (Coral Wings) |
| Worst month for delays | August (19.6 min) |
| Best month for delays | January (10.3 min) |

## Dashboard Pages & Visuals

### 1. Average Delay by Airline
Compares the average delay minutes across different carriers, highlighting which airlines struggle most with schedule adherence.

![Average Delay by Airline](PHOTO-2026-11-08-11-54-16.jpg)

### 2. Cancellation Rate
Examines the percentage of canceled flights per airline to reveal reliability gaps independent of delay durations.

![Cancellation Rate](PHOTO-2026-11-08-11-56-06.jpg)

### 3. Monthly Delay Trend
Tracks seasonal variations in average delay minutes across the year to identify peak operational stress periods.

![Monthly Delay Trend](PHOTO-2026-11-08-12-02-20.jpg)

### 4. Distance vs. Delay
Explores the correlation between flight distance (Km) and average delay times.

![Distance vs Delay](PHOTO-2026-11-08-12-02-20%202.jpg)

### 5. Customer Satisfaction by Feedback Category
Analyzes passenger survey scores broken down by feedback category and passenger class.

![Customer Satisfaction by Feedback Category](PHOTO-2026-11-08-12-04-47.jpg)

### 6. Operational Performance by Origin City (Map)
Visualizes geographical clusters of delay and operational metrics across global origin cities.

![Operational Performance by Origin City](PHOTO-2026-11-08-12-06-41.jpg)

## Key Findings

1. **Delays are fairly even across airlines, but "Unknown" is the worst.** Average delay runs from 13.0 minutes (Kestrel Air) to 22.8 minutes ("Unknown"). Among named airlines, SavannaJet (19.8 min), Iberic Air (19.6 min) and Cedar Air (18.9 min) lead the delays.
2. **Cancellations are a bigger gap than delays.** Andes Fly has the highest cancellation rate (12.93%), followed closely by Cedar Air (12.12%) and Northern Wing (11.36%). Coral Wings achieves the lowest cancellation rate among named airlines at 3.91%.
3. **Delays and cancellations are not the same problem.** Northern Wing maintains relatively low delays (14.8 min) alongside high cancellations. Conversely, Andes Fly exhibits mid-range delays but the worst cancellation rate. Only Cedar Air and SavannaJet perform poorly on both fronts.
4. **Delays have a clear seasonal pattern.** January records the lowest delays (10.3 min), whereas August peaks at 19.6 min, with March (18.3 min) and December (18.9 min) also experiencing severe delays.
5. **The map shows regional clusters.** Average delays by origin city range between 14.1 and 19.3 minutes. Higher-delay (red) clusters concentrate primarily in Europe, the US East Coast, and East Asia, while better-performing (green) regions appear in Australia, Africa/Middle East, and select parts of Asia.
6. **Satisfaction is lowest on specific touchpoints.** First class rates "Value for money" lowest (3.20) and "Baggage handling" low (3.40). Comfort stands out as the weakest overall category across classes (3.50 to 3.75), whereas First class rates "On-time performance" highest (4.40).

## Recommendations

1. **Fix cancellations first**, targeting Andes Fly, Cedar Air, and Northern Wing. A cancellation causes significantly more disruption to passengers than a minor delay.
2. **Target the worst airlines on both measures.** Cedar Air and SavannaJet require an immediate scheduling, resource, and operational review.
3. **Plan proactively for peak months.** Increase staff levels, optimize buffer times, and secure spare aircraft prior to August, March, and December.
4. **Focus on weak touchpoints:** Improve First Class value perception, baggage handling efficiency, and overall cabin comfort.
5. **Clean the data records for "Unknown" airlines.** Given they record the longest average delays, data hygiene must be prioritized before making strategic investments.

## Tools Used
- Tableau Public
- Python / Pandas (Data pre-processing)

## Data
- **Dataset:** Airline Performance, Flights, and Customer Satisfaction Survey Datasets (Public / Educational Analytics Dataset)

## How to Open
1. Download the `G04_EDS2233_Workbook.twbx` file from this repository.
2. Open it using **Tableau Desktop** or **Tableau Public Reader**.

## Author
**Sandun Lakshan Ranathunga**  
Business Analytics Undergraduate

---
*Built with AI assistance. Analysis and dashboard design completed independently.*
