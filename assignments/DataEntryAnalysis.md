### Question 1

The variables have different names between the datasets. 

The number of variables differ between datasets that appear to be measuring the same things.

The distribution of observations differs between sets. Two sets have Cuni and Chippo observations separated with distinct columns. The third has a single column specifying species instead.

There are blank data with no explanation. Unknown where the issue lies, if there is an issue with missing observations

There is no differentiation between similar observations on the same day. Unknown if they are taken at different times at the same location, same location at different times, or some combination thereof.

Not sure what the graphs will be used for but one is measuring Depth vs Cuni #/L and the other is Date vs Temp. The latter also seems to have a significant outlier that isn't explained. 

There is no index column.

### Question 2

The intention is to add more accurate date tracking with a boolean for AM/PM since it seems like that is a meaningful differentiator. I would also maintain the variable scheme dividing the two observation groups via their own columns.

I also added an index column.

| Index | Date | Time | AM | Depth | Cuni#/L | CuniColonySize | Chippo#/L | ChippoColonySize | Chla | Temp |
|-------|------|------|----|-------|---------|----------------|-----------|------------------|------|------|
|       |      |      |    |       |         |                |           |                  |      |      |
|       |      |      |    |       |         |                |           |                  |      |      |
