NBA 3-Point Evolution (2012–2024)

Project Overview
This project explores how the three-point shot has reshaped scoring and performance patterns in the NBA between 2012 and 2024.
Using Python and Tableau, I analyzed league and player data to uncover trends in 3-point volume, efficiency, and their overall impact on scoring.
The analysis includes:
Cleaning and merging multi-season NBA player datasets
Visualizing 3-point performance geographically across NBA teams
Running a regression model to evaluate how 3-point attempts drive total scoring
Performing a time-series forecast to predict future scoring trends (2025–2027)
Creating a Tableau storyboard that communicates the full data story visually

Objectives
Examine how 3-point shooting has evolved between 2012–2024.
Quantify the relationship between 3-point attempts and total scoring.
Visualize how teams across the league have embraced the 3-point era.
Forecast future scoring patterns based on historical data.

Data Sources
Primary Dataset: Basketball Reference – Player statistics from 2012–2024.
Time-Series Dataset: Aggregated season-level statistics created from player-level data.
All datasets were cleaned, merged, and analyzed using Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels).

Tools & Libraries
Programming:	Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, statsmodels)
Visualization:	Tableau Public, Matplotlib, Seaborn
Data Management:	Jupyter Notebook, CSV

Key Results & Insights
3-point attempts have increased dramatically since 2012, driving record-high league scoring averages.
The regression model (R² = 0.72) shows a strong positive correlation between 3-point attempts and total points scored.
Time-series forecasting projects that league scoring will continue to rise moderately through 2027.
Geographic visualization (in Tableau) displays how NBA teams have embraced the 3-point era, comparing total attempts and shooting efficiency by team location.
A Tableau map visualization highlights team-level 3-point performance across North America.
Each blue circle represents an NBA team, sized by total 3-point attempts and shaded by 3-point shooting percentage.
This interactive view makes it easy to compare shooting behavior and efficiency by geography, showing how widespread the 3-point revolution has become across the league.

Project Workflow Summary
Data Cleaning: Removed nulls, standardized columns, and restricted seasons to 2012–2024.
Exploratory Analysis: Visualized distributions and correlations between 3PM, 3PA, and total points.
Regression Analysis: Modeled the impact of 3-point attempts on scoring (R² ≈ 0.72).
Time-Series Forecasting: Applied ARIMA to project scoring through 2027.
Geographic Visualization: Created a Tableau map of team 3-point stats by location.
Final Storytelling: Combined findings into an interactive Tableau storyboard.

Links
Tableau Storyboard: View on Tableau Public
https://public.tableau.com/app/profile/shanta.maraj/viz/NBA3pt_17605668420720/Story1

The Tableau storyboard focuses on key visualizations and insights from the Python analysis to tell a cohesive final story.
