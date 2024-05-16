# Airbnb Superhost Analysis

## Kaggle & PPT Slides
**Presentation link**: [https://drive.google.com/file/d/170TFLGRsCNBma_Tcg4SLzSFYT-MpLZSu/view?usp=sharing](https://drive.google.com/file/d/170TFLGRsCNBma_Tcg4SLzSFYT-MpLZSu/view?usp=sharing) 
**Slides Deck link**: [https://docs.google.com/presentation/d/1bCKObMGPldZ-S3ZrWV_S6e3esE_7Ftse/edit?usp=sharing&ouid=113313002084083777814&rtpof=true&sd=true](https://docs.google.com/presentation/d/1bCKObMGPldZ-S3ZrWV_S6e3esE_7Ftse/edit?usp=sharing&ouid=113313002084083777814&rtpof=true&sd=true) 

## Introduction
This project examines the impact of Airbnb's Superhost status on a host's revenue generation. The Superhost badge is awarded to hosts who excel in hospitality based on specific criteria: number of trips hosted, response rate, completion rate for confirmed reservations, and number of 5-star reviews. We aim to determine which of these criteria most significantly influence revenue and whether achieving Superhost status correlates with financial benefits for hosts.

## Objectives
The primary objectives of this project are:
- To evaluate the impact of achieving Superhost status on a host's revenue.
- To analyze which Superhost criteria most significantly influence revenue.
- To provide insights for current and prospective Airbnb hosts to optimize their earnings.

## Data Source
Our research targets the Chicago Airbnb market using the `"airbnb_Chicago"` dataset, which contains 120,217 rows and 112 columns of data. The key data columns used include:
- Revenue
- Superhost status
- Number of bedrooms and bathrooms
- Listing type
- Cleaning fee
- Minimum stay requirements
- Number of photos
- Instantbook enabled
- Ratings and reviews

## Methodology
1. **Exploratory Data Analysis (EDA):**
   - Conducted `EDA` to compare Superhosts and Non-Superhosts in terms of revenue and property policies.
   - Analyzed the impact of various property attributes on revenue.

2. **Model Selection:**
   - Utilized a `Difference-in-Differences (DiD)` approach to compare revenue changes over time between Superhosts and Non-Superhosts.

3. **Regression Analysis:**
   - Built `regression models` to analyze the impact of Superhost status and other variables on revenue.
   - Performed `sensitivity tests` to refine the model and ensure robustness.

## Key Findings
- **Revenue Impact:** Achieving Superhost status does not significantly increase revenue.
- **Significant Factors:** Number of bathrooms and overall rating are significant factors across all periods. Adding a bathroom can increase revenue considerably.
- **Insignificant Factors:** Number of reviews and Superhost status itself are not as impactful on revenue.
- **Nightly Rate:** The interaction term for Superhost status in the nightly rate regression model was not significant, indicating no substantial effect on nightly rates.

## Recommendations
1. **Increase Bathrooms:** Hosts should consider increasing the number of bathrooms to boost revenue.
2. **Focus on Ratings:** Enhancing the overall rating is crucial for increasing revenue.
3. **Optimize Listings:** Ensure high-quality photos and detailed descriptions to improve listing appeal.

## Limitations
- **Geographic Scope:** The analysis is limited to Chicago.
- **Time Period:** The study focuses on evaluation periods 8 to 15.
- **Data Limitations:** Lack of data on competition, listing visibility, and service/amenities provided by hosts.


