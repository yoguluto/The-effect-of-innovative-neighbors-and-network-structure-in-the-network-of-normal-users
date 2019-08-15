# The-effect-of-innovative-neighbors-and-network-structure-in-the-network-of-normal-users
Data Access for the paper "The effect of innovative neighbors and network structure in the network of normal users"

In the file of UserNetworkData.csv,there are seven columns. The first one is the serial number of every record (start from 0 and has no real meaning). The second and third columns give the edgelist of user network in our research. Column "F" refers to the start node (i.e. Sender) of ties in the network and column "T" refers to the end (i.e.Reciever). The left columns show the time point when this tie emerged (In other words, the time point when this interaction happened). For convenience, we saved the time point as the exact date ("Date" column), the year of the date ("Year" column), the month of the date("Month" column), the day of the date("Day" column), the how many days has passed from 2007-01-01 to this date ("IntervalDays" column) separately.

In the file of UserNetworkData.csv, there are nine columns. Still, the first one is the serial number of every record(start from 0 and has no real meaning). The second columns("Date" column) is the exact time point when this idea was submitted. Besides this, we still save the time point as the year of the date ("Year" column), the month of the date("Month" column), the day of the date("Day" column), the how many days has passed from 2007-01-01 to this date ("IntervalDays" column) separately. The third column,"Status" column, shows the status of this idea and the fourth column, "User" column, shows who has submitted this idea. Status of idea is given by Dell, if it is "Implemented" or "Partially Implemented", we considered this is an effective idea in our research.The last column,"GoodIdea", is a dummy variable which shows if ideas are effective(1) or not(0).

Noting there is a user whose name is consisted of some special characters which can not be shown correctly under utf-8 code. We use blank to replace this user's name. So you may find a user with name of " " in the data. This is not a missing user. 

Additonal Information:
We uploaded the Panel Data we used in the panel regression as "PanelData.RData" addtionally. Since the data size will become quite large by saving as a ".csv" file , here we uploaded it in the ".RData" format which provided an effective compressing method. Another reason is that we processed our data mainly by R. The order of the variables (the columns) in the Panel Data is as follows:
1. The Number of Effective Idea Submission (the dependent variable)
2. The Constraint
3. The Neighbours’ Average Effective Idea Submission
4. The Frequency of Interactions
5.  Days Being Observed
6. Number of Neighbours
7. The Number of All Idea Submission
