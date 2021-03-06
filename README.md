# Election Analysis
## Overview of Election Audit
A Colorado Board of Elections employee asked for election audit of a recent local congressional election.
The audit shows the results for the following:
   1. The total number of votes cast in this congressional election.
   2. A breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   3. The county with the largest number of votes.
   4. A breakdown of the number of votes and the percentage of the total votes each candidate received.
   5. The winner of the election based on popular vote.

## Resources
* Data Source: election_results.csv
* Software: Python 3.9.6, Visual Studio Code, 1.38.1

## Election Audit Results
The audit of the election demonstrates that:
* There were **369,711** votes cast in the election.
* County votes breakdown:

County | Percentage of Votes | Number of Votes
:-------|:-----------------:|:--------------------:
Jefferson | 10.5% | 38,855
Denver | 82.8% | 306,055
Arapahoe | 6.7% | 24,801
* The largest county votes turnout is **Denver** with **82.8%** and **306,055 votes**
* The candidates votes results are:

Candidates | Percentage of Votes | Number of Votes
:-------|:-----------------:|:--------------------:
Charles Casper Stockham| 23.0%| 85,213
Diana DeGette| 73.8% |272,892
Raymon Anthony Doane|3.1| 11,606

* The winner of the election is:
  **Diana DeGette who received 73.8% of the votes and 272,892 votes!**
  
## Election Audit Summary
The power of this election audit python code is its ability to be reused in any election with minor modifications. For example,
you can change the election data source file by changing the folder and file name in the following code block:
```# Add a variable to load a file from a path.
file_to_load = os.path.join("Resources", "election_results.csv")
````
Replace "Resources" folder with the new folder name, and "election_results.csv" with the new election data csv file.

Also, you can save the new results to a different text files by replacing the folder name "analysis" and the file name "election_analysis.txt" with new folder and files names respectively.
```
# Add a variable to save the file to a path.
file_to_save = os.path.join("analysis", "election_analysis.txt")
```

