# Capstone Project: Python Application for Data Analysis

## Overview
This project was conducted for Book-Worm, a company specializing in online book subscription services. The primary goal was to analyze the impact of various media channels on the number of account registrations and measure their effectiveness.

## Objectives
- **Measure Media Contribution**: Quantify the influence of each media channel on account registrations.
- **Calculate ROI**: Assess the return on investment for each channel.
- **Forecast Future Performance**: Use historical data to make predictions and support decision-making.

## Key Findings
### Observations on Registrations:
- Monthly account registrations show significant fluctuations, with peaks observed in the middle (June) and end of the year.
- After each spike, registrations tend to decline to a lower average level before rising again.
- Sudden declines may indicate short-term campaigns or seasonal effects.

### Long-Term Trends:
- Growth observed from 2019 to mid-2020, followed by a gradual decline from mid-2020 to 2022.

### Seasonal Patterns:
- Cyclical trends with peaks and troughs every 6-12 months, influenced by time-of-year factors like summer or year-end periods.
- Minor oscillations occur approximately every 1-2 months.

### Advertising Insights:
1. **2019-2020**:
   - Peaks in advertising spend (May-June) align with registration spikes.
   - Significant increases in TV and Google Generic Paid Search budgets contributed to registration growth.
2. **Post-2021**:
   - More consistent TV ad budgets maintained stable registrations at relatively high levels.

### Channel-Specific Observations:
![image](https://github.com/user-attachments/assets/e3fc7a2b-4627-481b-b8e8-aa8e2c1001e4)

- **Google Display Impressions, Influencer Views**: High impressions or views do not necessarily convert into registrations.
- **Meta Impressions**: Positive correlation; increased impressions lead to higher registrations.
- **Google Generic Paid Search Impressions**: Registrations are unaffected by higher impressions, suggesting saturation or inefficiency.
- **TV GRP**: Registrations remain stable at low GRP levels, implying TV ads may require higher thresholds to be impactful.
- **Google Brand Paid Search Clicks**: Clear upward trend; significant registrations occur only with >4000 clicks.
- **YouTube Impressions**: Limited correlation with registrations, mainly boosting brand awareness.
- **Dates_School_Holidays**: Registrations increase during holidays, highlighting their impact.
- **Promotions**: Both competitor and internal promotions focused on 14-30 free days effectively influence registrations.

### Correlation Analysis of Channels:
![image](https://github.com/user-attachments/assets/2f75af69-fa53-4653-8856-057b36ce0763)

#### Channels with Strong Correlation:
- **Meta Impressions (0.66)**: Strongest correlation with registrations, indicating its significant impact on user acquisition.
- **Google Brand Paid Search Clicks (0.56)**: Plays a critical role in driving registrations.
- **Dates_School_Holidays (0.67)**: High correlation suggests school holidays significantly influence registrations.

#### Channels with Moderate or Low Correlation:
- **TV GRP (0.25)**: Slight positive correlation; TV ads may need higher GRP thresholds to create impact.
- **Google Generic Paid Search Impressions (0.16)**: Low correlation indicates inefficiency in driving registrations.
- **Promotion (0.14)**: Slightly positive; internal promotions assist but are not dominant drivers.
- **Influencers Views (0.12)**: Very low correlation, suggesting limited impact.

#### Channels with Negative or Insignificant Correlation:
- **YouTube Impressions (-0.43)**: Negative correlation indicates inefficiency in converting impressions to registrations.
- **Google Display Impressions (-0.01)**: Insignificant impact on registrations.
- **Competitors Promotion (-0.06)**: Slight negative correlation; competitor campaigns may marginally reduce registrations.

## Conclusion
![image](https://github.com/user-attachments/assets/94e4ae02-1f47-4c6f-8d22-88f1fd31d005)

Through data analysis, we identified key drivers of account registrations and evaluated the effectiveness of various media channels. Meta Impressions and Google Brand Paid Search Clicks were the most impactful channels, while YouTube Impressions and Google Display Impressions showed limited influence. School holidays emerged as a significant factor in boosting registrations. The insights from this analysis can help optimize future marketing strategies and allocate budgets more effectively to maximize ROI.
