# surfs_up

**Purpose**

Using SQlAlchemy, Temperature in June and December in Hawaii can be processed in an 'offline' database to provide results. By manipulating the temperature of the months June & December, we can easily see the statistics of temperature and see if the ice cream surf shop will be a success in Hawaii. 

**Results**

The key take-aways from the analysis can be summarize with the following:


![june_df](https://user-images.githubusercontent.com/99565016/163526223-acf23cd4-19c7-467e-90f1-08bd0e500c35.PNG)

***figure 1: June Database for temperature***




![december_df](https://user-images.githubusercontent.com/99565016/163526236-7132f29d-85e3-4168-af86-6f537f283c9f.PNG)

***figure 2: December Database for temperature***

1. The weather provided by the most active station shows that June's average temperature is higher than December's average temperature. This is expected as Summers tend to be hotter than Winters, though we can see that the difference is not significant. 

2. Another key difference between the two months is that Winter's minimum temperature is significantly different than its average compared to Summer's minimum temperature to its respective average temperature. Though the temperature is still considered warm, investors can expect a lower profit margin during the winter time with the provided data in figure 2. 

3. Last key point to take away from figures 1 & 2 is that June's standard deviation is lower than December's standard deviation. With increase standard deviation means that Winter can be expected to deviate from its average temperature of 71 degrees since it has higher spread. Though not significantly different, we can say with lower confidence that Winter will stay within a beach-ready weather in the 70's. 


**Summary**

*Recap*

With the analysis provided, we can report to the investors that Hawaii is a good location to open a surf ice cream shop since it appears that regardless of Summer or Winter, the beaches are always perfect for ice cream. One thing to note is the Winter's minimum temperature definitely drops to a brisk 56 degrees, which we can expect not too many people to buy ice cream. Another thing to note is that there are many data points provided by both months (>1000) indicating that we can trust the data provided. 

*Additional Queries*

1. What is the mode of each month? It's good for the investors to know what is the normal temperature for the month to expect swings or consistent income.

2. How would a histogram look like of the data presented? Investors will see general statistics but it definetly helps to provide a visual presentation of the data for key take-aways. 
