# Election_Analysis

## Project Overview
Sitting down with Tom and Seth, the tasks that need to be completed for the election audit are reviewed, and then the information needed by the Colorado Board of Elections is reviewed.
A dataset is provided, that includes ballot ID numbers, county names, and candidate names as well.
From this dataset, the following criteria are required to be identified and analyzed:
1.	Calculate the total number of votes cast.
2.	Get a complete list of candidates who received votes.
3.	Calculate the total number of votes each candidate received.
4.	Calculate the percentage of votes each candidate won.
5.	Determine the winner of the election based on popular vote.
## Resources
The following items were used to assist with the completion of this project:
•	Data Source: election_results.csv
•	Software: Python 3.6.1, Visual Studio Code 1.38.1
## Election-Audit Results
After conducting the analysis if the election, the following statements can be concluded:
•	There were 369,711 votes cast in this election.
•	The vote turnout for the counties are as follows:
o	The county of Jefferson tallied 38,855 (10.5% of the total vote count) votes.
o	The county of Denver tallied 306,055 (73.8% of the total vote count) votes.
o	The county of Arapahoe tallied 24,801 (6.7% of the total vote count) votes.
•	The county with the highest number of votes was Denver with 306,055 votes.
•	The candidates were: 
o	Charles Casper Stockham
o	Diana DeGette
o	Raymon Anthony Doane
•	The results for each candidate are as follows:
o	Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
o	Diana DeGette received 73.8% of the vote and 272,892 number of votes.
o	Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
•	The winner of this year’s election was:
o	Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
 
## Election-Audit Summary
To the election commission, the script utilized to run the analysis of this year’s election can be applied to any other type of election. Whether it be for elections for public office, elections for who won that year’s best ribs, or any other type of election. It is not just limited to the elections for who represents the residents of the counties. 
One way of modifying the script to appease the conditions of the required election is to change the variable names, as to identify the different components of the code in a much easier and organized manner. Rather than have “winning_county”, one may have “winning_ribs”, for example. The benefit of having legible code allows for any future analyzers to swiftly interpret the contents of the script and be able to make modifications as they see fit. Thankfully, some of the variables, such as “winning_candidate”, can be applied broadly and do not require much changing.
Another way to alter the script would be to be able to implement the results from the .txt file into a Graphics User Interface (GUI), so that the results appear in a nicer, and more professional, page. The knowledge to do so eludes me at this current moment, but as this is merely a suggestion, it could be implemented at a later date, and to then build upon the script to make it even better than it currently is.
