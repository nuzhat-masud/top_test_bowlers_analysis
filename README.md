# Analysis of all-time top bowlers in test matches

**Background**
<br>The greatest bowlers of all time has been listed in the dataset in separate rows according to total wickets they took in the span of their career as a cricketer. Along with wickets, their are other attributes used to extrapolate overall performance of each player over their career. 

**Attributes:**
 - Player - name of the players
 - Span - starting and ending year of the player's career
 - Mat - matches played 
 - Inns - innings played 
 - Balls - balls bowled 
 - Runs - Runs conceded
 - Wkts - Wickets taken 
 - BBI - Best Bowling in Innings
 - BBM - Best Bowling in Match
 - Ave - Bowling Average
 - Econ - Economy Rate = Average number of runs conceded per over  
 - SR - Bowling Strike rate 
 - 5 - number of times the player took 5 wickets in an inning
 - 10 - number of times the player took 10 wickets in an inning

**Analysis description**
<br>The steps of data analysis, processing and cleaning:
1. Importing necessary python packages
2. Reading the excel (.csv) file
3. Naming the new dataFrame
4. Finding the number of rows and columns
5. Descriptive Statistics of the dataset
6. Finding the data types and missing values
7. Renaming columns
8. Removing unnecessary columns
9. Splitting 'Player' column into 'Player' to include player names and 'Country' to include nationality of the player
10. Finding the bowlers who played at ICC
11. Finding the nationalities of the players
12. Splitting the 'Span' column into 'Start_year' to include the year bowler started playing and 'End_year' to include the ending year of the bowler
13. Finding the number of years the bowler was playing
14. Rearranging columns
15. Finding the bowlers with longest and shortest career span
16. Finding the bowler with lowest Economy Rate, Strike Rate and Bowling Average

**Reference** 
<br>Data Source: https://stats.espncricinfo.com/ci/content/records/93276.html
