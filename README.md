# Explanatory Data Visualization of Baseball Batting Analysis



####Summary:  

This visualization explains the batting trend of the MLB players across different height and weight categories. 
It has a author 
driven narrative where the trend of Batting average and Home runs scored has been shown across players of all heights 
available 
in the dataset (i.e. ranging from 65-80 inches) categorized by handedness.
Then it provides various options to the user to explore 
the visualization (user driven narrative). 
The user can explore the visualization for trends in the batting average and home runs, 
analyzing the count of players in each height / weight category. There are strong trends for batting average vs. height and weight.
There is a strong trend for home runs vs. weight. Also, there is a strong trend of the count of players vs. given height / weight
category.



####Design:  

The design choice for the visualization is driven by the idea to present the visual picture of the Batting trends of the MLB players
to the audience. There is a strong trend in the Batting Average vs. height with the shorter players having a better batting average 
than the taller players. Hence, decided to have this as the main theme of the visualization (author driven narrative). There is also 
a strong trend in Batting Average vs. weight of the players. Hence, have included it in the user driven narrative. Also, included 
option for analyzing on the count of players in the user driven narrative. The count of players will help identify the distribution 
of players in the different height and weight categories in the dataset. It was decided to have 4 sections on the Page. The heading 
section to display the main heading and the chart title on the top of the page. The nav section on the left side of the page to display the various options for the user to select to explore the visualization. To the right of the nav covering almost 3/4 of the page it was decided to have the graph section. The footer section at the bottom of the page has been used to display the footnotes of the visualization. It was decided to use bubble chart to display the points with height / weight on the x-axis and have the Batting Average / count on the y-axis as this is the trend that I am trying to convey in the visualization. Each point has been encoded to convey additional information of handedness and average home run scored. Used colour to show the handedness as it will aid in distinguishing and comparing the trend for different handed players. Chose lighter colours and avoided Red and Green colour variants in the visualization. Since there are only 3 categories to be represented colour is a good choice to represent handedness. 
The average Home runs scored in the visualization varies from 0 to around 250. The size of the point would be able to 
efficiently convey this information. The heading section has the name of the visualization which is static and the main heading of the page. The second heading has been made dynamic to display the appropriate chart title based on the options selected by the user. A legend for the handedness category is provided on the upper right corner in the graph section. In the footnote it was decided to mention that the size of the circle denotes the average Home run. A hover text has been provided for the circles which gives the values of average home run and count of players in the category. It was decided to provide a button for the user to click to refresh the page to display the visualization for the revised options selected.   

The url for the initial visualization (Version 1) is http://bl.ocks.org/rajesh-g-nair/raw/1ddc7254ee650ee1a17a/   

Based on the feedback received on this initial visualization, the following changes were made:   
1. The animation was made a little faster  
2. Some of the points in the chart was overlapping with the heading. Hence, moved the chart a little below  
3. The chart title was changed to read as y-axis vs x-axis instead of x-axis vs y-axis  
4. Added footnotes to provide some information about the dataset  
5. Removed the refresh button and instead added the logic to change the visualization when the user changes the option  
6. Added footnotes to denote the scale used for the size of the bubble and to convey more specific information about what the size of    the bubble represents  

The url for the first revision (Version 2) is http://bl.ocks.org/rajesh-g-nair/raw/bd2bea212fb13850f6e7/   

Based on the feedback received on the first revision, the following changes were made:   
1. The title of the visualization had "Base Ball" instead of "Baseball" which was corrected  
2. Removed the text from the footnote about the scale used for the size of the circle and added a legend instead to denote this  

The url for the second revision (Version 3) is http://bl.ocks.org/rajesh-g-nair/raw/b4a46f21d1b94c4e4667/   

Based on the feedback received on the second revision, the following changes were made:   
1. The chart area was reduced in width and the legends were shifted to right so that the legend's are outside the area of the chart  
2. Removed the footnote saying that the size of the circle denotes the "Average Career Home run"  
3. Changed the heading of the Legend denoting the size of the circles to read as "Average Career Home runs"  
4. The position of the three larger circles and the numbers placed over them in the legend was changed to be evenly spaced  

The url for the third and final revision (Version 4) is http://bl.ocks.org/rajesh-g-nair/raw/03f983d6adec8852123c/  

####Feedback:   
The Udacity discussion forum was used to get the feedback on the visualization   

The link to the discussion forum used for getting the feedback is as below   
https://discussions.udacity.com/t/need-feedback-on-my-project-data-visualization-of-baseball-data/41012   

####Resources:   
Udacity training material   
http://stackoverflow.com/   
