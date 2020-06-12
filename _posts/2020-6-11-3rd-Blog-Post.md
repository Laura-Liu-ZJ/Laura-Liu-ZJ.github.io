---
layout: post
title: Outline of the Project 1
---

## Abstract
This project includes three parts, the first part is an introduction, which response to describing the JSON and discussing the possible packages/functions that are available for reading JSON data into R. This part also contains the introduction of NHL and NHL Data. To study the NHL data, I get the 5 JSON data sets from API. And reorganize those data sets by selecting some variables, creating some variables, and combining relevant data sets. 

The second part is the processes of Exploratory Data Analysis (EDA). In this project, I picked out the "best" franchise and the "worst" franchise according to the EDA part for teamtotalData and seasonData. Then I also tried EDA on the differences between the "best" franchise and the "worst" franchise from goalieData and skaterData. 

The last part is the conclusion from the above analyses, which shows the "best" franchise is Golden Knights (ID: 38) and the "worst" franchise is Coyotes (ID: 28), which might because of the number of goalie and skater, the goalies' ability of resistance and the skaters' aggressive assists.

## Content
1. Introduction
   - Description of JSON Data
     - What it is?
     - Where does it get used?
     - Why is it a good way to store data?
   - Discussion on R packages for reading JSON data
   - NHL & NHL Data
     - What is NHL?
     - Get the NHL data
     - Reorganize the data sets
2. Exploratory Data Analysis
   - winPct & futureWin in teamtotalData
     - Treat the winPct as categorical data
     - Treat the winPct as numeric data
   - mfWinRatio & steadyWin in seasonData
     - Treat the mfWinRatio as categorical data
     - Treat the mfWinRatio as numeric data
   - The “best” franchise and the “worst” franchise
   - The difference of goalie between Golden Knights and Coyotes
   - The difference of skater between Golden Knights and Coyotes
3. Conclusion

## Vignettes
Here is the link of [my frist Project](https://laura-liu-zj.github.io/ST558Project1/).

