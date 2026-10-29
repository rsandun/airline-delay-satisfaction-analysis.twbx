# Airline Delays, Cancellations and Passenger Satisfaction Analysis

An analysis of airline performance covering flight delays, cancellations, seasonal patterns, regional differences and passenger satisfaction. The goal is to find which airlines and months cause the most problems for passengers, and what the business should fix first.

## Business Questions
- Which airlines have the longest delays?
- Which airlines cancel the most flights?
- Are delays and cancellations the same problem?
- Which months and regions are the worst for delays?
- What do passengers in each class like least?

## Key Numbers
| Measure | Value |
|---|---|
| Average delay range across airlines | about 13 to 23 minutes |
| Worst cancellation rate | 12.9% (Andes Fly) |
| Best cancellation rate (named airlines) | 3.9% (Coral Wings) |
| Worst month for delays | August (19.6 min) |
| Best month for delays | January (10.3 min) |

## Dashboard Pages

### 1. [Page name, e.g. Delay Analysis]
[One line about what this page shows.]

![Page 1](screenshots/1-page-name.png)

### 2. [Page name, e.g. Cancellations]
[One line about what this page shows.]

![Page 2](screenshots/2-page-name.png)

### 3. [Page name, e.g. Passenger Satisfaction]
[One line about what this page shows.]

![Page 3](screenshots/3-page-name.png)

## Key Findings

1. **Delays are fairly even across airlines, but "Unknown" is the worst.** Average delay runs from about 13 minutes (Kestrel Air) to about 23 minutes ("Unknown"). Among named airlines, SavannaJet (19.8), Iberic Air (19.6) and Cedar Air (18.9) are the worst.
2. **Cancellations are a bigger gap than delays.** Andes Fly has the highest rate (12.9%), then Cedar Air (12.1%) and Northern Wing (11.4%). Coral Wings is the lowest among named airlines (3.9%).
3. **Delays and cancellations are not the same problem.** Northern Wing has low delays (14.8 min) but a high cancellation rate. Andes Fly is mid-range on delay but worst on cancellations. Only Cedar Air and SavannaJet are weak on both.
4. **Delays have a seasonal pattern.** January is the lowest (10.3 min). August is the peak (19.6), with March (18.3) and December (18.9) also high. July and October dip to about 16.
5. **The map shows regional clusters.** Average delay by origin city ranges from 14.1 to 19.3 minutes. The worse (red) circles are mostly in Europe, the US east coast and East Asia. The better (green) ones are in Australia, Africa/Middle East and parts of Asia.
6. **Satisfaction is lowest on a few specific things.** First class rates "Value for money" lowest (3.2) and "Baggage handling" low (3.4). Comfort is the weakest category overall (3.5 to 3.75). First class rates "On-time performance" highest (4.4).

## Recommendations

1. **Fix cancellations first**, especially at Andes Fly, Cedar Air and Northern Wing. A cancelled flight is a bigger problem for a passenger than a 15-minute delay.
2. **Target the worst airlines on both measures.** Cedar Air and SavannaJet need a scheduling and resource review.
3. **Plan for peak months.** Add extra staff, buffer time and spare aircraft before August, March and December.
4. **Focus on the weak touchpoints:** First class value for money, baggage handling and comfort.
5. **Fix the "Unknown" airline records.** They have the worst delay, so the data should be cleaned before decisions are made.

## Tools Used
- [Power BI / Tableau / Python / Excel: write what you used]

## Data
[Name and source of the dataset]

## How to Open
1. Download `[file-name]` from this repository.
2. Open it in [tool name].

## Author
Sandun Lakshan Ranathunga
Business Analytics Undergraduate
