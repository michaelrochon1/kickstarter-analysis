# Kickstarting with Excel

## Overview of Project
We have been tasked with providing our client, Louise, an analysis of other Kickstarter campaigns so that she may have a clear picture of the outcome of her out Kickstarted play as far as launch date and funding goal data is concerned. With this in mind we have chosen to give her the outcomes of Kickstarter campaigns in the theatre category based on launch date and the outcomes of the plays sub-category based on the funding goal.

### Purpose
The purpose of using these particular parameters is to provide a transparent and easy to discern picture to a dataset that contains thousands of data points and a large number of categories. This analysis may also provide the client with information should she choose to fund another play through the Kickstarter environment. We have provided charts to ensure that this data can be easily understood.

## Analysis and Challenges
When working with a dataset with this many datapoints and an array of categories and subcategories it is always a complicated feat to boil those down to a manageable analysis. Futhermore, when sifting through that amount of data there is bound to be a significant amount of data that is not applicable to a particular analysis. Upon first sight, its clear that the higher the goal the less liekly a Kickstarter will succeed, although not impossible.

### Analysis of Outcomes Based on Launch Date
While the launch month does seem like it would be an irrelevant point of analysis, however upon further analysis it does seem like the percentage of successful kickstarters in the theatre category does decrease in the winter months. Whether this is because the proximity to holiday months and a lack of extra funds in a household, or if it is a symptom of a lack of households wanting to leave the house during the cold winter months is unclear. But it is clear that the number of successful theatre Kickstarters declines after the high point in May.

### Analysis of Outcomes Based on Goals
Analysis of outcomes based on the goal target provides much clearer, and arguably more useful, outcomes. As the goal becomes larger there it is clear that the chance for success, for a play, is much higher the lower the goal. There is an odd point in the 30,000 to 44,999 mark that is difficult to account for but is likely is due to the small sample size. The over 80% fail rate in plays with goals above 50,000 is a clear indicator of the lower likelihood of success.

### Challenges and Difficulties Encountered
Personally, I encountered no difficulties in completing analysis, however I could imagine that COUNTIFS could create some issues with the number of criteria ranges required in the analysis of outcomes based on goals. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Firstly, you have the highest number of successful theatre based Kickstarters are in the months of May and June, and therefore would be the best time to launch a Kickstarter of that nature. Secondly, the number of successes and failures are equal in December and therefore would be the riskiest month to launch a theatre Kickstarter.

- What can you conclude about the Outcomes based on Goals?
The larger the goal is the larger the possibility that the outcome will be a failure. Especially once the goal is above 50,000. On the other side of the coin, the lower the goal the higher the chance you'll have a successful Kickstarter in the 'play' subcategory.

- What are some limitations of this dataset?
The dataset does not give specifics on individual backer amount of donations or the date which the pledges were made. Therefore, it is distinctly possible that many of the successful Kickstarters may have succeeded at the very end of their lifecycles to ensure success. Along those same lines, it does not include the length of the campaigns - an important part of the Kickstarter campaign ecosystem.

- What are some other possible tables and/or graphs that we could create?
Average donation per backer would be a very interesting point of analysis. Also subcategory vs region could also supply some interesting opportunities for analysis. Staff pick vs success would allow us to examine the success of the staff pick badge on Kickstarter campaigns.
