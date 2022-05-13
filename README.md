# Election_Analysis

## Overview of Election Audit:
In this project, we orginally used Python to automate vote counting for an election audit to return the results of the winning candidate. For this challenge, we then went a little further and focused on the voting information more specific to the counties. This included total voters in each county, percentage of votes per county, and finding the county with the most votes.

## Election Audit Results

- Total Votes: 369,711
  - ***Denver: 306,055 (82.8%)***
  - Jefferson: 38,855 (10.5%)
  - Arapahoe: 24,801 (6.7%)
  
- Denver had **significantly** more voters than the other counties

- Our candidates, along with their vote totals and percentage votes are as follows:
  - ***Diana DeGette: 272,892 (73.8%)***
  - Charles Casper Stockham: 85,213 (23.0%)
  - Raymon Anthony Doane: 11,606 (3.1%)
  
- From this, we clearly found that Diana DeGette won the election, having recieved 73.8% of the votes

<img width="302" alt="Screen Shot 2022-05-12 at 11 03 37 PM" src="https://user-images.githubusercontent.com/103979087/168209065-bc488d76-56ab-4b0d-b0e1-fc60f0bfbaf3.png">


### Election-Audit Summary:
As we have observed, we succesfully added to our original PyPoll that only included vote totals and percentages specific to the candidates, so that it now includes that same information for the counties participating in the election. This means two things for the script that we wrote:

  1) It can be continually added to in order to include even more data, like finding what percentage of each county votes went to which candidate. This would highlight where they are most popular so that they can adjust their campaigning in the future to see where they could put in more work to recieve more of the votes next time around.
  
  2) The script could easily be manipulated to read a different set of Election Results by changing the file_to_load csv. path (pictured below) and adjusting the data accordingly. Writing the script was the hard part, and now this allows for a quick analysis of large amounts of data with a less intensive amount of time manipulating details to accomodate new information, saving the election audit team lots of time.
  
 <img width="527" alt="Screen Shot 2022-05-12 at 11 26 56 PM" src="https://user-images.githubusercontent.com/103979087/168211315-47b05575-a5f4-4fda-960d-34c294049697.png">

 
### Resources:
V.S Code 1.66.2
Python 3.7.6
Election_Results.csv
