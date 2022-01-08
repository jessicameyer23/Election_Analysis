# Election_Analysis
## Overview of Election Audit:

I have been hired to complete an election audit for the Colorado Board of Elections.  The purpose of this audit is to certify and validate the results of a recent local congressional election.  This will help the county feel confident in the results.  In addition, the Colorado Board of Elections will be able to use my program to certify other election results in the future for other races, not only in Colorado, but potentially across the United States. While the analysis could be performed manually, performing it in python will enable it to be used in the future and save money and time.

## Election-Audit Results

I have included a picture of my print command line below, which includes a summary of the election results, but I will also walk through them line by line below.

![image_name](https://github.com/jessicameyer23/Election_Analysis/blob/main/analysis/Picture%20of%20Command%20Line%202022-01-08%20111008.png)

1.  Calculate the total number of votes cast:  The total number of votes cast in the election was 369,711
2.  Get a complete list of candidates who received votes:   There were 3 candidates who received votes: Diana DeGette, Charles Stockham and Raymon Doane.
3.  Calculate the total number of votes each candidate received:  Diana DeGette received 272,892 votes and Charles Stockham received 85,213 votes.  Raymon Doane received the least amount of votes, receiving a total of only 11,606 votes.
4.  Calculate the percentage of votes each candidate won:  Diana DeGette received 73.8% of the votes and Charles Stockham received 23% of the votes.   Raymon Doane received only 3.1% of the votes.
5.  Determine the winner of the election based on popular vote:  Diana DeGette was the winner of the election, receiving 272,892 votes, which was 73.8% of the total votes. 

Another interesting fact is that the largest county turnout was Denver, 306K votes, and almost 83% of the total votes.  It appears that Denver likely the most populous county in Colorado based on the significant percentage of votes compared to the next most popular county of Jefferson having less than 39K votes.

## Election-Audit Summary:

I would propose that this script be used for auditing other elections.  This program has many different use cases and could save the state of Colorado significant time and resources.  Examples are included below:
1.  The script could be used to audit a congressional election in a different part of the state of Colorado.  We would need to load the csv file of that county, but could use our code to create county lists and a county votes dictionary.
2.  The script could be used to audit a national election.  In this case, instead of potentially having a county list and county votes dictionary, you would have a state list and state votes dictionary.
3.  The script could also be used locally just to audit a local school board election, where they may have "voting districts" instead of counties.  In this case you would create a voting district list and district votes dictionary. 

