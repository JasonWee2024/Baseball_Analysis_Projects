# Baseball Analytics Projects  

Welcome to my baseball analytics portfolio! This repository showcases my skills in **R Programming**, **Data Analysis**, and **Advanced Baseball Statistics**. Each project explores unique aspects of baseball performance, combining data insights with visualization to provide meaningful takeaways.  

## Table of Contents  
- [Park Factor Analysis](#park-factor-analysis)  
- [Kiké Hernández Performance Analysis](#kiké-hernández-performance-analysis)  
- [Burnes Pitching Analysis](#burnes-pitchers-analysis)

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


# Corbin Burnes Pitching Performance Analysis

## Objective
Compare Corbin Burnes' pitching performance before and after introducing the cutter to his arsenal in 2020, focusing on key metrics such as ERA, FIP, WHIP, K/9, and BB/9, as well as changes in his pitch repertoire.

## Key Metrics
ERA (Earned Run Average)

FIP (Fielding Independent Pitching)

WHIP (Walks + Hits per Inning Pitched)

K/9 (Strikeouts per Nine Innings)

BB/9 (Walks per Nine Innings)

Pitch Mix: 4-seam fastball, slider, cutter, curveball, changeup, sinker

Whiffs

## Key Insights
The addition of the cutter in 2020 significantly improved Burnes' performance, particularly in limiting walks and generating whiffs.
His pitch mix evolved, with the cutter becoming his primary pitch, leading to marked improvements in key metrics like K/9 and WHIP.
Burnes' ERA and FIP decreased, and he became more effective at preventing hard contact, especially on non-fastball pitches.

## Files
- **Burnes_pitchers.Rmd:** Full analysis and visualizations in R Markdown.

## Full Analysis
Explore the full project [here](https://jasonwee2024.github.io/Baseball_Analysis_Projects/Burnes%20Cutter/Burnes_pitchers.html).  

## Metrics Glossary
FIP: Fielding Independent Pitching, which measures a pitcher's performance based on strikeouts, walks, and home runs.

K/9: Strikeouts per nine innings, indicating a pitcher's ability to miss bats.

BB/9: Walks per nine innings, measuring a pitcher's control.

WHIP: Walks plus hits per inning pitched, which shows how effectively a pitcher prevents base runners.

Whiffs: Swinging strikes, showing how often batters miss a pitch.

## Feedback and Collaboration  
I’m always looking to improve my skills and learn from others. If you have feedback on my methods or want to collaborate on a baseball analytics project, feel free to reach out!  
