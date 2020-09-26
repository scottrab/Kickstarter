# Kickstarter


Written Analysis for Kickstarter Data


#Purpose
The purpose of the asssignment was to uncover trends in new theater opening and their success rate.  Additionally, trends relating to the outcomes in comparison to the goals for a dollar amount raised were also discovered.  To discover these trends i created 2 graphs which clearly display the relationships we have with the theater and plays data within the Kickstarter dataset.

#Outcomes based on goals
One of the graphs i made revealed a trend that is worth noting: plays that had lower goal dollar amounts, on average, were the most consistently successful in terms of their outcome.  We can see this relationship here: https://github.com/scottrab/Kickstarter/blob/master/Outcomes_vs_Goals.png?raw=true. After seeing this graph, it is clear that there is almost an inverse relationship between the goal's dollar amount and whether or not the play was successful.  The rate of success tapers off as money increases, however there is a slight jump nearing $50,000 which is interesting and would be worth looking into.

#Outcomes based on launch date
In addition to the graph shared above, I sorted through data on various kickstartes and had to convert Unix calendar dates to real dates and then created a pivot table and graph accompanying the pivot table to clearly display trends in theater outcomes in relation to their launch data. This graph can be seen here: https://github.com/scottrab/Kickstarter/blob/master/Theater_Outcomes_vs_Launch.png?raw=true.  After seeing the data visually, it is clear that we have an increased success rate for theaters launched really peaked in late April through May, following by a decrease moving into the winter.  In addition, failures remain constant, varying minimally throughout the year, especially compared to the success, which shows a high degree of seasonality. 

#Conclusion and closing thoughts
This was a time consuming task however it did feel good to be done with it once i figured it out how to properly format the dates for the pivot table to only display months, a challenge I had due to the intial UNIX date given in the inital data set.  Following converting this date to a normal date, the pivot table still used the raw numers in UNIX form so I needed to figure out a way to get it to work.  After some time searching online, I ended up copying the dates as a raw value which i was then able to import into the pivot table to finally have my data in the proper format.  In addition to the two graphs i created above, some other analysis could have been useful.  For example, we could have created a graph to display success and failures for other types of kickstarters and compare them to see if there is any commonality and then a conclusion can be drawn from there. 

-Scott Rabinowitz





