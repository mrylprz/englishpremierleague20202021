<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Photos/Premier%20League%20Logo.png" width="500">
</p>

# Football Analytics: Market Value Analysis of English Premier League 2020/2021
<br>

## Introduction
Welcome to the "Football Analytics: Market Value Analysis of English Premier League 2020/2021" repository! This project aims to provide a comprehensive analysis of the relationships between various variables and Key Performance Indicators (KPIs) with the market values of players and clubs in the English Premier League for the 2020/2021 season.  

**IMPORTANT** This project was written in 2021 and the current market values of the teams and players may have changed. All references and findings are based at the current market values at the time of writing.

## Data Source
The dataset utilized in this study contains football statistics for the English Premier League 2020/2021 season, up to Game Week 22. It includes data for all 582 players and 20 clubs, covering a total of 214 matches. The market values of each club and player were obtained from the open-source football database - [Transfermarkt](https://www.transfermarkt.us).

## Focus of the Study
While the entire Premier League season is considered, particular emphasis is also placed on Leicester City as a club, and three selected players from their roster. However, the analysis extends beyond this subset to evaluate the relationships between the variables and KPIs with market values across all clubs and players in the Premier League.

**NOTE** You can explore other clubs in the Team Level Dashboard to compare their statistics against each other.

## Performance Indicators (PIs)
In the context of sports analytics, a performance indicator is a variable or a combination of variables used to measure and describe performance in a given sport. These indicators are essential for assessing and understanding successful outcomes within the sport.

  ### Classification of Performance Indicators
  The dataset provides a range of performance indicators that operate at different levels, including league, match, team, and player levels. Research by Hughes and Bartlet (2002) identified the most common performance indicators used to assess player performance, which are further divided into five categories:
  1.	Physiological
  2.	Tactical
  3.	Technical - Defensive
  4.	Technical - Attacking
  5.	Psychological
  This study primarily focuses on the Technical Defensive and Technical Attacking categories, as they are most relevant to the analysis of market values.

## Factors Influencing Market Values
Apart from performance indicators, several external factors contribute to a football player's market value. Factors such as age, contract duration, position, skills, brand value, and the league in which they play all have a significant impact on a player's total market value (Williams, 2021).

## Repository Structure
This repository is organized as follows:
*	Dashboard File: PowerBI file used for data exploration, analysis, and visualization.
*	Data: Contains the dataset used in this analysis.
* KPIs: Table of PIs used in this analysis
* Photos: Background images, logos used in building the dashboard
*	Visualizations: Dashboards and graphs generated
  *	Dashboard Snapshots: Dashboards focused on Leicester City (Team Level and Player Level)
  *	Player Level Graphs: Player Level PIs vs Market Value Graphs
  *	Team Level Graphs: Team Level PIs vs Market Value Graphs 
*	References: List of Studies and Articles used as references


## Key Performance Indicators (KPIs)
### Team Level
Table 1 summarises the KPIs and variables used to evaluate the team’s performance. Each KPI is plotted against the market values of all the teams to determine their relationship.  
  
Table 1. Team Level KPIs/Variables  
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/KPIs/Team%20Level%20KPIs.png" width="600">
</p>
  
Apart from these technical indicators, Club Average Age, a physiological indicator, also has a relationship with the club’s market value (refer to Figure A-7) where the market values are higher when the average of all the players’ ages are from 24-26.  
  
Figure A-7. Club Average Age vs Club Market Value  
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Team%20Level%20Graphs/Figure%20A-7.%20Club%20Avg%20Age%20vs%20Club%20Market%20Value.png" width="400">
</p>  
   
The dashboard in below shows the performance of the club, Leicester City, based on the KPIs in Table 1. According to Transfermarkt (2021), the team’s current league position is 3rd but their market value ranks at 8th place. 
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Team%20Level%20Dashboard%20-%20Leicester%20City.png" width="700">
</p>   

Based on the twenty-two (22) matches they participated in, Leicester City has 13 wins (59%), 6 losses, and 3 draws. Their average goals per match is lower than the League Level Average. The data shows that Leicester City are at a disadvantage when playing in their home field at 19%. Nevertheless, 53% of the time, the ball is in their possession across their matches.  Comparing their offensive and defensive skills, goal accuracy is slightly lower than goals conceded, while %FTS (matches they failed to score) is lower than %CS (matches that they managed to prevent their opponent from scoring). Therefore, their offensive play is stronger than their defence. Their home disadvantage is also seen in their FTS count and count of goals conceded where the home statistics are higher. 

**Other Team PIs vs Market Value:**
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Team%20Level%20Graphs%20-%20KPIs%20vs%20Market%20Value.jpg" width="550">
</p>  

### Player Level
Table 2 summarises the KPIs and variables used to evaluate the players’ performance. Each KPI is plotted against the market values of all the teams to determine their relationship.
  
Table 2. Player Level KPIs/Variables  
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/KPIs/Player%20Level%20KPIs.png" width="600">
</p>    

The player’s position also contributes to the market value of the player (refer Figure B-4).  The Club Score Contribution’s (%CSC) effect on the market value varies per position. Forwards and Midfielders are more affected by this KPI than Defenders and Goalkeepers. Whereas the effect of change in Clean Sheets/Matches Played(%CS/MP), a measure for defensive skills, is the same regardless of position.
  
Figure B-4. Position vs Market Value
  
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Player%20Level%20Graphs/Figure%20B-4.%20Position%20vs%20Market%20Value.png" width="400">
</p>  


Like the team level, the player’s age also affects the player’s individual market value (refer to Figure B-5) where the market values are higher when the player’s age is between 23 and 29.  
  
Figure B-5. Age vs Market Value 
  
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Player%20Level%20Graphs/Figure%20B-5.%20Age%20vs%20Market%20Value.png" width="400">
</p>  

**Other Player PIs vs Market Value:**
<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Player%20Level%20Graphs%20-%20KPIs%20vs%20Market%20Value.jpg" width="550">
</p>  


The dashboards snapshots below shows the performance of the 3 chosen players from the club, Leicester City, based on the KPIs mentioned in Table 2. The player, Wesley Fofana, was assigned to the analyst while the two players, Jamie Vardy, and James Maddison were chosen because Vardy ranked 1st place for the Top Scorers within the club while Maddison had the highest market value within the club.
Referring to the dashboards and the KPIs that are found to affect a player’s market value, the following insights regarding the players were derived:


**Jamie Vardy – Forward**

<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Player%20Level%20Dashboard%20-%20LC%20-%20Jamie%20Vardy.png" width="700">
</p>  

Findings:
* Although he ranked 1 in the club top scorers, his market value contribution is relatively lower than the other players. 
* Although his position is forward, he contributes to the overall defence of the team indicated by a relatively high value of %CS/MP.
* His PER is above the team’s average with 11 goals, 5 assists, and 19 goals conceded.
* He performs better in ‘away’ matches.
* His age is beyond the age range of players with high market value.
 
**James Maddison – Midfielder**

<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Player%20Level%20Dashboard%20-%20LC%20-%20James%20Maddison.png" width="700">
</p> 

Findings:
* He has the highest market value contribution among all the players.
*	His club score contribution is also high given that he is a Midfielder.
*	His relatively high %CS/MP (higher than Jamie Vardy) shows his contribution to the team’s defensive strength.
*	His PER is above the team’s average with 6 goals, 5 assists, and 16 goals conceded but lower compared to Vardy.
*	He performs well on offensive in home matches while better on the defensive in away matches.
*	His age is within the age range of players with high market value.


**Wesley Fofana – Defender**

<p align="center">
   <img src="https://github.com/mrylprz/englishpremierleague20202021/blob/main/Visualizations/Dashboard%20Snapshots/Player%20Level%20Dashboard%20-%20LC%20-%20Wesley%20Fofana.png" width="700">
</p>  

Findings:
*	According to Transfermarkt, he is the latest transfer to Leicester City (his contract is new).
*	His club market value contribution is higher than Vardy.
*	His PER cannot be calculated because he does not have any goals and assists.
*	He also has a relatively high %CS/MP showing his contribution to the team’s defensive strength.
*	He performs well on offensive in home matches while better on the defensive in away matches.
*	His age is beyond the range of players with high market values.


## Conclusion and Findings:
By assessing the football statistics of the English Premier League Season 2020/2021 along with market values from Transfermarkt, these are the findings on variables and KPIs with significant contributions to the players and teams’ market values:
*	The KPIs, Points per Game, Goals per Match, Average Possession, Goal and Shot Accuracy and  %Clean Sheets have the same upward trend line when plotted against the market value at the team level, indicating that higher values/ratings for these KPIs have a positive effect on the team’s market value.
*	Higher values for %FTS and %Conceded result to decrease in team’s market value. 
*	The club’s average age also affects the club’s market value because at the player level, age is a huge factor on the individual players’ market values. 
*	Overall team score is important at the team level while individual goals, assists, and participation (minutes played and appearances) are crucial to certain positions only: forwards and midfielders.
*	%CS/MP is a measure of a player’s defensive skills, but it affects a player’s market value regardless of the position.
*	Across all teams, forwarders and midfielders have the highest average market values. However, this does not apply to Leicester City where Midfielders and Defenders have the highest average market values.

## Acknowledgments
We would like to express our gratitude to the open-source football database - [Transfermarkt](https://www.transfermarkt.us) for providing valuable data for this analysis.
Thank you for your interest in this football analytics project! I hope you find the insights valuable and informative.
