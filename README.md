# FBS-CollegeFootballData


We share the college football network data, in particular the schedules of NCAA Football Bowl Subdivision (FBS) teams 
in the U.S. between 2014-2017, used in the "Optimal Hierarchical Clustering on a Graph" paper by
Kahvecioglu G. and Morton D. 

Contents of directory: 
- conference_labels.csv: FBS teams and their associated conferences/subconferences 
- FBS team schedules: headers --> [team ID, team name, opponent ID, opponent name, date, location]
  - fbs2014.csv: 2014 schedule 
  - fbs2015.csv: 2015 schedule 
  - fbs2016.csv: 2016 schedule 
  - fbs2017.csv : 2017 schedule 

Some notes about the data: 
* The FBS data only contains the regular-season games
* We do not include the independent teams
* We do not include the teams that did not play all four seasons
* Thus, in total we look at 122 teams
* Contains schedules played within the FBS network


