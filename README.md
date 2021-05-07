# Election_Analysis_Week_3

##Overview of Election Audit
A Colorado Board of Elections employee provided me with the following tasks to complete an election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

After this was completed, I was then tasked with completing a list of how many votes each county registered, the percentage
of votes each county had of the total votes, and the county that had the largest turnout. This was saved on a text file, with all the data then displayed in an easy to read format.

## Resources

- Data Source was election_results.csv
- I used the following software: Python 3.7.6, Visual Studio code.

## Election Audit Results

The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates involved were:
    - Charles Casper Stockham
    - Diane Degette
    - Raymon Anthony Doane
 - The results were as follows:
    - Charles Caspter Stockham received 23.0% of the votes, with 85,213 votes.
    - Diane Degette received 73.8% of the votes, with 272,892 votes.
    - Raymon Anthony Doan received 3.1% of the votes, with 11,606 votes.
 - The winner of the election was:
    - Diane Degette who received 73.8% of the votes, with 272,892 votes.
 - The counties where votes were pulled from were:
    - Jefferson
    - Denver
    - Araphoe
 - The results were as follows:
    - Jefferson reported 10.5% of the votes, with 38,855 votes.
    - Denver reported 82.8% of the votes, with 306,055 votes.
    - Araphoe reported 6.7% of the votes, with 24,801 votes.
 - The county with the largest turnout was Denver.

With the code I had created, the following output was returned in the terminal:

![Results from Terminal](https://github.com/swlim314/Election_Analysis_Week_3/blob/65189046089400ac35a0603ef2e4c19437eb12fe/Images/Results%20from%20Terminal.png)

This was then saved into a text file, with the output as follows:
![Results saved to text file]https://github.com/swlim314/Election_Analysis_Week_3/blob/b59bd6356f90131d3fcf2edfb3e84bba72e856e1/Images/Results%20saved%20to%20text%20file.png
    
 ## Election Audit Summary
The script that I created can be used with some modifications for any type of election and can be updated to take into account demographic data, such as age groups and ethnicity. This can be done by initializing lists and dictionaries similar to the candidate_options, candidate_votes or the county_list and county_votes used in my code. By having a similar structure with using a for loop to count the amount of voters in certain age groups or ethnicities, the election commision can get a better idea about which candidates were popular with which groups. 
Another way this script could be used for any type of election, with the code updated is to store election data over different election periods. This would again require initializing another list and dictionary to store additional data that would be iterated through a for loop. This would allow the election commision to determine if there were
any shifts in voter turnout.
