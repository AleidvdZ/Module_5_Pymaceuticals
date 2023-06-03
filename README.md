# Module_5_Pymaceuticals
Module 5 Challenge - plotting

5/25
-Counted unique mouse ID
https://sparkbyexamples.com/pandas/pandas-count-unique-values-in-column/#:~:text=To%20count%20unique%20values%20in%20the%20pandas%20dataframe%20column%20use,size%20to%20get%20the%20count

For “Get the duplicate mice by ID number that shows up for Mouse ID and Timepoint” input I got some suggestions from Ryan C. to use unique and loc and ended up figuring out just by using unique in a print.  Output is a bit different than in the starter but the right mouse ID is returned.

5/26
Selecting all items in a column based on a specific value https://www.statology.org/pandas-select-rows-based-on-column-values/
Calculating stats used previous assignments, no outside resources

5/28
Worked on summary table - no issue

5/30
Used previous assignments to figure out panda plot and needed some formatting help from this sources:
https://stackoverflow.com/questions/14824456/edit-the-width-of-bars-using-pd-dataframe-plot

Setting xticks labels from index names
https://stackoverflow.com/questions/43717739/matplotlib-set-xticks-to-column-labels-to-corresponding-index

6/2
Removing Index heading https://stackoverflow.com/questions/29765548/remove-index-name-in-pandas

NOTE that the percentage of male/female in the pie chart end up as 49.6% and 50.4% which does not exactly match the output shown in the starter code but which I believe to be correct. This is as a result of 123/248*100 = 49.5967742% rounds to 50.0% and 125/248*100 = 50.4032258 which rounds to 50.4%

Madplotlib pie https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.pie.html
adding %'s and removing legend https://digestize.medium.com/how-to-create-a-matplotlib-pie-chart-annotated-with-percentages-and-labels-3f7274845142

Quartiles etc. section 
    needed to reduce df based on row condtion https://www.geeksforgeeks.org/selecting-rows-in-pandas-dataframe-based-on-conditions/

    Following instructions, don't need what I did in 32 but instead needed this to find max timepoint:
    https://stackoverflow.com/questions/15705630/get-the-rows-which-have-the-max-value-in-groups-using-groupby

    Used this to merge on two columns https://realpython.com/pandas-merge-join-and-concat/

     "The interquartile range (IQR) is the difference between the 75th and 25th percentile of the data." 
     https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.iqr.html



