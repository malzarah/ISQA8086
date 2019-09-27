# Problems with the dataset:-
1. Missing values in all 3 datasets  In Zoo Temp Main file there are missing values in Temp column, next  missing values are found in 
Pond dataset again in Temp column.
2. Data are collected for 3 days , however the sample is not equally distributed. 
6/7/2011 has more vlaues, 6/4/2011 and 6/9/2011 have only few values.
3. Data is not normalized, they are unevenly distributed.
4. All the datasets just have date, they don't mention the time when the data was collected, as mentioned in the problem that they change with time.
5. Dataset doesn't show any correlation between depth and any other parameters, doing a T-test and other liner regression models, I couldn't find any relation between depth and other parameters. Possibly the sample size is less.
6. There seems to be a lot of outliers, which makes it difficult to make any statistical model.

# Section 2 :- New way of organizaing the data
Add time variable and see how they change.

Date| Time |Depth| Cuni #/L|Cuni|ColonySize|Chippo #/L|Chippo|ColonySize|Chla|Temp|

Date| Time |Depth| Cuni #/L|Cuni|ColonySize|Chippo #/L|Chippo|ColonySize|Chla|Temp|

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
