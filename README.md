# Election Analysis

## Overview of Election Audit
To complete the election audit of a recent local congressional election, the Colorado Board of Election requested the following tasks:

1. Calculate the total number of votes cast.
2. Calculate the voter turnout for each county.
3. Calculate the percentage of votes from each county out of the total count.
4. Determine the county with the highest turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.
9. Provide a written analysis.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.8, Visual Studio Code, 1.73.1

# Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The counties  were:
  - Arapahoe
  - Denver
  - Jefferson
- The county results were:
  - Arapahoe County voters cast 24,801 votes, totaling 6.7% of the total.
  - Denver County voters cast 306,055 votes, totaling 82.8% of the total.
  - Jefferson County voters cast 38,855 votes, totaling 10.5% of the total.
- The county with the largest turnout was Denver County; in this county, the voters cast 306,055 votes, totaling 82.8% of the total.

- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote, totaling 85,213 votes.
  - Diana DeGette received 73.8% of the vote, totaling 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote, totaling 11,606 votes.
- The winner of the election was Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Election Audit Summary
Thank you for the opportunity to provide these services to your electorate. The developed code can continued to be used in future electiions with minor updates. The first, and possibly most important update to the script, will be the election results csv file (which should be named with the year) and ensuring that the path to reference the appropriate file is correct.

![This is an image](https://github.com/mmstrouth/Election_Analysis/blob/5801379ccdccda39bf5c20a9500b050aa9057d58/Resources/correct_path%20_reference.png) 

I also recommend that you ensure that your new csv file follow the same set-up as the first provided with the following column headers, listed in order: ballot ID, county name, and candidate name. If the set-up is not the same the following code will need to be updated to reference the correct column. It's important to note that in this coding language, counting of columns starts with 0, therefore the ballot ID was 0, county name was 1, and candidate name was 2; thus, the number in [] would need to be updated with any column header changes. 

![This is an image](https://github.com/mmstrouth/Election_Analysis/blob/5801379ccdccda39bf5c20a9500b050aa9057d58/Resources/correct_column_reference.png)



