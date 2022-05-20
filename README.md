# Election Analysis
## Overview of Election Audit
The purpose of this election audit analysis was to retrieve additional information as per the election commissions’ request. This includes what the voter turnout was for each county, the percentage of votes from each county out of the total count, and which county had the highest voter turnout.


## Election-Audit Results
<img width="266" alt="election_analysis" src="https://user-images.githubusercontent.com/64383146/169443977-0887a7e9-e46f-4ff1-80f0-49935bb9775b.png">

- There were 369,711 votes cast in the election.
- The county votes were:
   - Jefferson county had 38,855 votes, 10.5% of the vote.
   - Denver county had 306,055 votes, 82.8% of the vote.
   - Arapahoe county had 24,801 votes, 6.7% of the vote.

The county of Denver had the largest number of votes, making up a majority of the votes.

- The candidates and their votes were:
   - Charles Casper Stockham received 85,213 votes, 23% of the vote.
   - Diana DeGette received 272,892 votes, 73.8% of the vote.
   - Raymon Anthony Doane received 11,606 votes, 3.1% of the vote.
- The winner of the election was:
   - Diana DeGette, who received 272,892 votes and 73.8% of the vote.

## Election-Audit Summary
This script, with some modifications, can be used for any election.

One way that it can be used is by loading a different file into this section of the code:
 - file_to_load = os.path.join("election_results.csv")

By substituting "election_analysis.csv" with any other csv file that has other county election results, the script will be able to be used for those elections. Replacing this csv file would mean that we could have more candidates and multiple counties that the code would be able to take into account and create an output for.

Another modification that can be made is that when the csv file is changed, this script can be used for other types of elections, other than county. The parts of the code that would need to be changed would be like:

<img width="106" alt="county_ex" src="https://user-images.githubusercontent.com/64383146/169453920-de7dad24-11f3-4f18-8f88-5ee0bb1bc692.png"> <img width="180" alt="county_ex2" src="https://user-images.githubusercontent.com/64383146/169453930-8d3bf9ab-8efe-4d65-b883-5d449528068d.png">

Wherever it says "county" would need to be changed to fit the type of election it would be for.
