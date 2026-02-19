# Football Manager 24 – Squad Optimization & Performance Impact Analysis

## Project Overview
This project evaluates the impact of a data-driven squad selection strategy implemented during a 32-game league season in Football Manager 2024.

The objective was to determine whether structured player selection based on contextual opponent strength and player performance attributes could significantly improve match outcomes without major squad reinforcements.

The intervention was implemented after the first 16 league matches. Performance before and after the optimization strategy was compared. 

## Problem Statement

The team was underperforming in the first half of the season, with a low unbeaten rate and high goals conceded.

*Key Question:*

Can structured, data-informed squad selection improve competitive performance without major transfer window changes?

## Methodology

### Baseline Performance Matches (1-16)
* **Unbeaten Rate:** 31.25%
* **Goals Scored:** 21
* **Goals Conceded:** 40
* **Goals per Game Scored:** 1.31
* **Goals per Game Conceded:** 2.50
* **Goal Difference per Game:** -1.19

![image alt](https://github.com/Ddmnetso/Football-Manager-24-Squad-Optimization-Performance-Impact-Analysis/blob/f2b9e8e38007d1a1475f93b5cb4641e3fac2875c/Screenshot%202026-02-19%20164950.png)
![image alt](https://github.com/Ddmnetso/Football-Manager-24-Squad-Optimization-Performance-Impact-Analysis/blob/fafe366115ed1c1b4aed050fb29e9f6a22e11b0e/Screenshot%202026-02-19%20165002.png)

## Intervention Strategy
After Matchday 16:

1. Developed weighted player evaluation model in Google Sheets
2. Identified “Big Game” performers based on attribute metrics
3. Segmented opponents into tiers:
    + Top 7 teams
    + Mid-table competitors
    + Relegation-threat teams
4. Allocated squad selection based on contextual opponent difficulty
5. No significant January transfer reinforcements introduced

## Phase 2: Post-Optimization Performance (Matches 17–32)
* **Unbeaten Rate:** 62.5%
* **Goals Scored:** 29
* **Goals Conceded:** 23
* **Goals per Game Scored:** 1.81
* **Goals per Game Conceded:** 1.44
* **Goal Difference per Game:** +0.37

![image alt](https://github.com/Ddmnetso/Football-Manager-24-Squad-Optimization-Performance-Impact-Analysis/blob/d70e0a1f48181210bbde8a7e846a8f34a7cbbe4b/Screenshot%202026-02-19%20164847.png)

## Results

### Unbeaten rate
Increased from 31.25% to 62.5%
100% relative improvement

### Defensive performance
Goals conceded per game reduced from 2.50 to 1.44
42% reduction

### Offensive performance
Goals scored per game increased from 1.31 to 1.81
38% improvement

### Net performance swing
Goal difference per game improved by +1.56
Shifted from -1.19 to +0.37 per game

## Interpretation
The implementation of tier-based squad optimization was associated with:
* Improved defensive stability
* Increased scoring output
* Significant improvement in match outcomes
* Structural performance shift without squad overhaul

While causality cannot be fully isolated due to potential confounding variables (fixture variance, morale effects, regression to mean), the magnitude of change suggests meaningful impact from selection optimization.

## Analytical Techniques Used

* Before/after comparative analysis
* Contextual segmentation (opponent tier classification)
* Performance normalization (per-game metrics)
* Outcome tracking across fixed time window

## Limitations
1. Non-randomized intervention
2. External game mechanics influence results
3. Potential variance in opponent strength distribution across halves

## Future work could include:
* Expected goals (xG) comparison
* Regression modeling to estimate contribution of selection strategy
* Sensitivity analysis on player weighting model

## Tools Used

* Google Sheets (player evaluation model)
* Manual performance tracking
* Match data aggregation
* Comparative statistical analysis

## Google sheets link

[Google Sheets Link](https://docs.google.com/spreadsheets/d/1fQAiFo-hQ3n5xDixbQxcpO2aIgnpLvzgKBpbMCuaXyM/edit?usp=sharing)
