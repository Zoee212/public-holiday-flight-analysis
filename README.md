# How to Find Better Flight Options During Public Holidays for Students and Teachers

## Overview
This project analyzes flight options for students and teachers who mainly travel during public holidays. It focuses on finding a better balance between **price** and **comfort** by examining how flight prices and comfort-related features change before, during, and after major holiday periods.

## Problem
For students and teachers, travel dates are often restricted by academic and work schedules. Public holidays may be one of the few realistic opportunities to travel, but flights during these periods are often more expensive and less convenient. This project explores how ticket prices and comfort-related features vary around holiday periods, so that users can make more informed travel decisions.

## Target Users
- Students
- Teachers
- Other travelers with limited flexibility during public holidays

## Research Question
How do flight prices and comfort-related features change around major public holidays, and how can students and teachers use this information to find better flight options?

## Data Scope
- **Origin:** Shanghai
- **Destinations:** Singapore, Seoul, Tokyo
- **Holiday periods:** Labour Day Holiday and National Day Holiday
- **Time window:** selected dates before, during, and after each holiday period

## Comfort Indicators
This project uses the following indicators of comfort:
- whether the flight is **direct**
- whether the flight departs during **00:00–05:59** (defined in this project as a red-eye flight)
- **number of stops**

## Data
The dataset includes the following variables:
- destination
- departure date
- holiday period
- holiday stage
- ticket price
- departure time
- whether the flight is direct
- number of stops
- record type

**Data source:** Skyscanner  
**Website:** https://www.skyscanner.com/  
**Access date:** 21 April 2026  
**Collection method:** Manual searches of flight options from Shanghai to Singapore, Seoul, and Tokyo during Labour Day and National Day holiday periods  
**Data format:** Manually collected in Excel and saved as CSV for analysis  
**Number of records:** 72  

To improve consistency, the searches were conducted using the same general settings, including origin city, passenger type, cabin class, trip type, and currency.

## Methods
This project uses Python to:
1. clean and organize the manually collected flight data
2. compare prices across destinations and holiday stages
3. analyze direct flights, red-eye flights, and stop patterns
4. identify options that better balance price and comfort for the target users

## Key Findings
Based on the analysis, the main findings are:

1. **Prices tend to be higher before holidays**  
   Flights departing shortly before a public holiday often cost more than flights after the holiday period.

2. **Destination matters**  
   Among the selected destinations, some routes are consistently more affordable than others during holiday periods.

3. **Direct flights usually cost more**  
   Direct flights are more convenient, but they often come with a price premium compared with indirect flights.

4. **Comfort often comes at a higher price**  
   Flights with more comfortable features—such as direct routes, fewer stops, and non-red-eye departure times—are often more expensive, although some good-value exceptions still exist.

## How to Run
1. Open `flight_analysis.ipynb`
2. Make sure the required Python libraries are installed
3. Place the dataset file in the `data/` folder
4. Run the notebook from top to bottom

## Files
- `README.md`
- `flight_analysis.ipynb`
- `data/flights.xlsx`
- `figures/`

## Output
The notebook produces charts and analysis that help compare:
- price changes across holiday stages
- destination-level price differences
- direct vs indirect flight trade-offs
- red-eye vs non-red-eye options
- more balanced flight choices for students and teachers

## Limitations
This project has several limitations:
- The dataset is relatively small and manually collected
- Flight prices can change over time
- The analysis focuses only on selected dates, destinations, and one departure city
- The results reflect the options visible on Skyscanner at the time of data collection

## Demo Video
A 1–3 minute demo video is included in the final submission.

## Author
Zhe.Shen2402
## Student Number
2469589
