# Baseball Analytics Projects  

Welcome to my baseball analytics portfolio! This repository showcases my skills in **R Programming**, **Data Analysis**, and **Advanced Baseball Statistics**. Each project explores unique aspects of baseball performance, combining data insights with visualization to provide meaningful takeaways.  

## Table of Contents  
- [Park Factor Analysis](#park-factor-analysis)  
- [Kiké Hernández Performance Analysis](#kiké-hernández-performance-analysis)  

---

# Park Factor Analysis  

## Objective  
Analyze park factors across MLB stadiums to understand how different ballpark dimensions and environments influence player performance.  

## Key Metrics  
- **Park Factor (PF):** Measures how a ballpark impacts scoring and hitting compared to the league average.  
- **Home vs. Away Performance Adjustments:** Identifies differences in player stats based on game location.  
- **xwOBA:** Combines exit velocity, launch angle, and strikeouts/walks to estimate expected on-base performance, independent of luck or ballpark effects.  

## Key Insights  
- **Arenado’s Home Performance:**  
  - Excels on fastballs at Coors Field, with high Total Hits and Home Runs.  
  - Coors Field’s hitter-friendly environment amplifies Arenado’s success, especially against fastballs.  
- **Seager’s Away Performance:**  
  - Thrives on the road, outperforming his home stats in Total Hits and Home Runs.  
  - T-Mobile Park’s pitcher-friendly environment likely suppresses his offensive output.  
- **Comparison of Pitch Type Approach:**  
  - Arenado adapts better to non-fastball pitches both at home and on the road.  
  - Seager relies more heavily on fastballs, struggling against pitch variation.  

## Files  
- **ParkFactor.Rmd:** Full analysis and visualizations in R Markdown.  

## Full Analysis  
Explore the full project [here](https://jasonwee2024.github.io/Baseball_Analysis_Projects/ParkFactor/ParkFactor.html).  

---

# Kiké Hernández Performance Analysis  

## Objective  
Compare Kiké Hernández’s regular-season stats with his exceptional postseason performance, focusing on splits such as home vs. away and pitch type.  

## Key Metrics  
- Batting Average (BA), On-Base Percentage (OBP), Slugging Percentage (SLG), BABIP  
- Splits: Home vs. Away, RHP vs. LHP, Fastballs vs. Other Pitches  
- **xBA, xOBP, xSLG:** Advanced metrics estimating expected performance based on contact quality and plate discipline.  

## Key Insights  
- Hernández consistently outperforms in the postseason, excelling against right-handed pitchers and non-fastball pitches in away games.  
- His regular-season stats, while less remarkable, highlight his unique ability to rise to the occasion in critical moments.  

## Files  
- **Hernandez_Performance.Rmd:** Full analysis and visualizations in R Markdown.  

## Full Analysis  
Explore the full project [here](https://jasonwee2024.github.io/Baseball_Analysis_Projects/Hernandez%20Performance/Hernandez_performance.html).  

---

## Metrics Glossary  
- **xwOBA:** Expected Weighted On-Base Average, combining contact quality and strikeouts/walks.  
- **xBA:** Expected Batting Average, estimating the likelihood of a hit based on contact quality.  
- **xOBP:** Expected On-Base Percentage, including walks, HBP, and contact quality.  
- **xSLG:** Expected Slugging Percentage, evaluating the likelihood of extra-base hits based on contact quality.  

---

## Feedback and Collaboration  
I’m always looking to improve my skills and learn from others. If you have feedback on my methods or want to collaborate on a baseball analytics project, feel free to reach out!  
