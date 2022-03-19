# Election Analysis with PyPoll
## Colorado Election Audit and Analysis
The goal of this analysis was to use Python to read a .csv file containing voting results for an election consisting of three candidates across three counties in Colorado. The final output came in the form of a total vote tally, vote counts and percentages for each candidate, a determination of the winning candidate with winning vote count and percentage, vote counts and percentages for each county, and a determination of the county with the largest voter turnout.

## Election Audit Results
* Total votes cast in the election: 369,711
* At the county level, the results were as follows:
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
* County with the largest turnout: Denver
* Results at the candidate level:
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)
* Diana Degette won the election for 272,892 votes, or 73.8%.

<img width="406" alt="terminal_output" src="https://user-images.githubusercontent.com/100387078/159139639-7b864a5c-a829-4f53-a80f-139fa45baa28.png">



## Conclusion
The election commission should use the script to analyze data from future elections. 

The script could be modified to iterate through the header row so as to be able to adjust the analysis for different dataset formats.

The script could also be modified to analyze other data associated with elections – like individual voter information, voting location, the dates and times that ballots were cast, and ballot type (e.g., mail-in, paper, electronic).
