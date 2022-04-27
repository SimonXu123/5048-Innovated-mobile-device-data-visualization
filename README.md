# Project description
## Project outline:

Applied Tableau to conduct data visualization analysis of which company tried to create the most innovative products or new market along the year from 2003 to 2012.

## Project method: 

Method 1: Clustering analysis (lead the market)

***The clustering analysis can be used to group different mobile devices with similar attributes into categories, the first coming out product in a group always can be considered as the leader in a specific area.***

For mobile devices, CPU (system processing power), screen size, storage, RAM and Pixel Density will significantly affect customers’ preference. To better analyze the result, we classify the multi-dimension visualization into 2 parts: One part is considering the features of CPU clock, RAM, Pixel density, Storage as tech index. Another part is classified in terms of Display Diagonal, Width, Length, Volume, Mass as size indices.

Then we used the K-means algorithm to cluster those two indices. For different clusters, we can choose the products coming in the first two years from 2003 to 2012. For each cluster, we can find pick up the first product (shown as sample cluster). So these first-coming out products can be represented the new market that leads in each cluster. For the user interaction, we apply the highlight function to the graph. Which can help viewers quickly locate the year that they want to analyze and avoid the distraction from other years (shown as cluster dashborad 1).

Method 2: Outlier analysis (Innovative)

***Because an outlier is also a good way to look at which company try to create a new market with different size of mobile devices*** 

As shown in dashboard 2, I pick out the outliers for each attribute, including CPU, Diagonal, and Volume; And then created a dashboard that includes three visualizations for each variable. The values for each mobile device are the outliers based on the boxplot in the previous section. In order to give the reviewer a better visualization to read the non-visualization part (Lecture W9-Evaluation), we use the size of a bubble instead of a single dot to represent the number of outliers for each year. In order to present a better visualization, I used Bubble chart and Voronoi diagram visualized different companies in tech index and size index separately based on the outliers. (shown as tech index outliers and size index outliers)

## Project result:

It can be easily found that Samsung company is the dominant part of outliers (reflect the specific company tries to create a new product), among these three variables and contributed to all of the dimension parts, followed by HTC, which only contributed to CPU and Volume part. Therefore, we consider Samsung. And in the clustering data visualization(reflects the specific company’s product are successful and followed by another company), we can also find Samsung is the company that leads the different mobile devices market.

