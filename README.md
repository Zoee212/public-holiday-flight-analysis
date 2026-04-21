# How to Find Better Flight Options During Public Holidays for Students and Teachers

## Overview
This project analyzes flight options for students and teachers who can only travel during public holidays. It focuses on finding a better balance between **price** and **comfort**.

## Problem
Flights during public holidays are often more expensive and less convenient. This project explores how flight prices and comfort-related features change around holiday periods, so that users can make better travel decisions.

## Target Users
- Students
- Teachers
- Other travelers with limited flexibility during public holidays

## Data Scope
- **Origin:** Shanghai
- **Destinations:** Singapore, Seoul, Tokyo
- **Holiday periods:** Labour Day Holiday and National Day Holiday
- **Time window:** 7 days before, during, and 7 days after each holiday

## Comfort Indicators
This project uses the following indicators of comfort:
- whether the flight is **direct**
- whether the departure time is **between 00:00 and 06:00**
- **number of stops**

## Research Question
How do flight prices and comfort-related features change around major public holidays, and how can students and teachers use this information to find better flight options?

## Data
The dataset includes:
- destination
- departure date
- holiday period
- ticket price
- departure time
- direct flight or not
- number of stops

**Data source:** Skyscanner (https://www.skyscanner.com/)
**Access date:** 21 April 2026
**Collection Method**: Manual search for flight options from Shanghai to Singapore, Seoul, Tokyo during Labour Day and National Day holiday periods
- **Data Format**: Excel file with 72 records covering various departure dates and flight options

## Methods
This project uses Python to:
1. clean and organize the flight data
2. compare prices across dates and destinations
3. analyze comfort indicators
4. identify options that better balance price and comfort

## Key Findings
Based on the analysis, the main findings are:

1. **Price peaks before holidays** – The average ticket price before holidays (1,577 CNY) is much higher than after holidays (840 CNY), a difference of nearly 50%. However, students and teachers often cannot travel after holidays due to school/work schedules.

2. **Seoul is the most affordable destination during holidays** – Among the three destinations, Seoul has the lowest average price during the holiday period (1,331 CNY), while Tokyo is the most expensive (1,443 CNY).

3. **Direct flights cost a premium** – Direct flights are on average 300 CNY more expensive than indirect flights, which may be worth it for travelers who value time but not for budget-conscious students.

4. **Comfort comes at a cost** – Higher comfort scores (direct flights, non-red-eye, zero stops) are associated with higher prices. Non-red-eye flights are available at similar prices to red-eye flights for most routes, making them a better choice for comfort.


## How to Run
1. Open `flight_analysis.ipynb`
2. Install required libraries
3. Run the notebook step by step

## Files
- `README.md`
- `flight_analysis.ipynb`
- `data/` (if needed)
- `figures/` (if needed)

## Demo Video
To be added.

## Author
[Zhe.Shen2402]
