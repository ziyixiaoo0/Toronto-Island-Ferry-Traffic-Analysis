# Toronto Island Ferry Traffic Analysis

## Background
This project combines my passion for data and my love for Toronto Island. As a Toronto resident who often visits the island, I recently noticed long ferry wait times and was curious about the factors behind them. By exploring and analyzing real-world data, I aimed to identify trends and showcase my skills as an early-career data scientist.

## Project Goal
Earlier this year, ferry wait times reached record levels. I wanted to find out: Were we actually experiencing record-breaking visitor numbers, or was something else driving these delays?

![Lineup](images/lineup.jpeg)

## Data Source
The analysis is based on open data from the City of Toronto:
- [Toronto Island Ferry Ticket Counts Dataset](https://open.toronto.ca/dataset/toronto-island-ferry-ticket-counts/)

This dataset includes information on ticket sales, redemptions, and timestamps. Since ticket sales can occur in advance, I focused on ticket redemptions to reflect actual ferry usage month by month.

## Analysis Steps
1. **Data Preprocessing**:
   - Converted timestamps to year/month format to capture trends over time.
   - Focused on redemptions to represent actual island visitors, as opposed to sales.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed seasonal trends, year-over-year changes, and anomalies in visitor counts.

## Results
### Key Findings
- **Seasonality**: July and August consistently draw the highest ferry traffic.
- **Peak Years**: The highest redemption counts were in 2018, 2016, and 2019, despite the population growth since. This suggests other factors, like wait times and ferry experience, may influence ferry use.
- **2024 Summer Impact**: Despite two ferries being out of service, August 2024 saw 322,173 redemptions, close to the 2018 peak of 394,291.

### Yearly Redemption Counts
| Year | Ticket Redemptions |
|------|---------------------|
| 2015 | 212,928            |
| 2016 | 365,416            |
| 2017 | 22,784             |
| 2018 | 394,291            |
| 2019 | 304,074            |
| 2020 | 84,942 (COVID Impact)|
| 2021 | 147,422 (COVID Impact)|
| 2022 | 349,082            |
| 2023 | 341,157            |
| 2024 | 322,173            |

- **Anomalies**: The drop in 2017 coincides with flooding that impacted the island, reducing ferry access and visitor numbers.
  
### Insights
Not every problem requires a forecasting model, but a data scientist's role often involves identifying key patterns and providing valuable insights. In this case, although ferry usage didn’t reach historic highs, wait times were still the longest I’ve seen in years, likely due to service constraints. Understanding these nuanced factors is crucial for informing city planning and resource allocation.

## Conclusion
This project underscores the importance of trend analysis in public transportation and highlights how external factors, such as ferry maintenance and natural events, impact service availability and wait times.

## Next Steps
Future analyses could explore:
- Correlations between weather patterns and ticket redemptions.
- Comparisons with water taxi usage to gain additional insights into visitor behavior.

## About Me
I'm an early-career data scientist, eager to bring value to projects that blend data and real-world impact. If you have any advice or would like to discuss data science further, I’d love to connect over a coffee chat!
