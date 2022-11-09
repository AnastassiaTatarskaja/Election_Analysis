# An analysis of election results in Colorado

## Overview of Election Audit

The code was written for Colorado Board of Elections using Python, Visual Studio Code and Git  to extract information from CSV file and analyze the results of the congressional election. Once the code was ran in Python terminal the following results were displayed in the output:

![image](https://user-images.githubusercontent.com/107759305/200898865-6cbf020c-28d3-4662-8465-3ee890104859.png)


Election Results section provides the total number of votes: 369,711. County Votes represents percentages and number of votes in Jefferson, Denver and Arapahoe counties. The following section displayed a winning county, Denver with 82.8% of the votes (306,055 votes). Next section shows three candidates and the breakdown of votes per candidate. Finally, last section identifies the Winner of the congressional election, vote count and percent of votes received. 


## Election-Audit Results

- There were 369,711 votes cast in the congressional election.

- There were three counties represented in this election: Jefferson, Denver, and Arapahoe. In Jefferson County there were 38,855 votes cast in    
  the election, which makes up 10.5% of the total count. In Denver county, 306,055 votes were cast, which makes up 82.8% of the total votes. 
  Finally, in Arapahoe county, 24,801 votes were cast, which makes up 6.7% of the votes.

- Denver had the largest number of votes cast: 306,055. 

- There were three candidates in this election: Charles Casper Stockham, Diana DeGette, and Raymon Anthony  Doane. Charles received 85,213 
  votes, which makes up 23% of the total votes. Diana received 272,892 votes, with 73.8% of the total votes. Raymon received 11,606 votes, 
  which makes up 3.1% of the total votes. 

- Diana DeGette was the winner of the election with 272,892 votes with makes up 73.8% of the total votes. 


## Election-Audit Summary

The Python script that was written to analyze congressional results in Colorado can be used for other elections. Take a look at Python excerpt script below which shows the logic for adding variable to load and then save a file from path:

![image](https://user-images.githubusercontent.com/107759305/200899131-65ddd84d-9b46-4043-8354-ccb8739b79a5.png)


If we modify the names of the files that we load from and save to, then any CSV file can be used to analyze election results. Additionally, we could refactor the python script to accept generic CSV files. 

