# Pricing-Strategy
Applying hypothesis testing to analyze the economics between flat rate pricing and Name Your Own Price strategies.

A field experiment has been conducted at an amusement park. Participants rode a roller coaster and were photographed during the ride. Afterward, each rider chose whether or not to purchase a print(s) of the photograph that was taken.

The experiment itself placed each rider into one of four conditions:

• $12.95 flat-rate price, i.e., FR

• $12.95 flat-rate price with 50% of revenue going to charity, i.e., FR Charity

• Name Your Own Price, i.e., NYOP

• Name Your Own Price with 50% of revenue going to charity, i.e., NYOP Charity

The charitable partner was a nationally recognized patient-support foundation. Two datasets from the experiment have been provided to you in comma-delimited files for your analysis.

**Datasets**

**Description of “Sales.csv”**

This dataset contains the number of photos sold, the number of riders, and the total merchandise revenues for each of the four conditions. Each condition was in place for 2 days (two rows of data) except for the last condition, NYOP Charity, which was in place for 3 days.

**Variables**

• Condition = A factor with four levels, matching each of the possibilities described above: FR, FR Charity, NYOP, and NYOP Charity

• NumberSold = The total number of photos purchased by consumers on a given day under the condition described

• Riders = The total number of riders placed into the condition on a given day under the condition described

• MerchandiseRevenues = Ancillary revenues related to merchandise purchased by riders at a location adjacent to the ride. Revenues are in US dollars.

**Description of “NYOP.csv”**

This dataset contains more specific information related to the NYOP and NYOP Charity conditions. Each row represents the purchasing behavior of a rider who made a purchase. Information on the condition of the rider, the number of photos purchased, and the price chosen by the rider have been collected.

**Variables**

• Condition = A factor with two levels, NYOP and NYOP Charity, capturing any rider who was in one of the two Name Your Own Price conditions

• Number = The total number of photos purchased by a given rider

• Price = The price chosen by the rider and paid in US dollars.

**Analysis**

You have been asked to carefully study the results from this field experiment to answer several questions your company has about the effectiveness of these different pricing strategies. In particular, you have been asked to write a memo that summarizes your findings. Below, we provide some guiding questions to help you in your exploration.

**Flat Rate Pricing**

When considering the two flat-rate pricing conditions, FR and FR Charity, is there a difference between the proportion of purchases?

1. What are appropriate null and alternative hypothesis to compare population proportions?
2. The appropriate test statistic for the difference between two population proportions is given by p¯1−p¯2p¯1(1−p¯1)n1+p¯2(1−p¯2)n2√, and with the large number of samples you can go ahead and assume the sampling distribution is normally distributed. Is the difference significant at the 5% level?
3. What is the p-value associated with the test statistic?
4. Interpret what this p-value means.

**NYOP Pricing**

When considering the two NYOP pricing conditions, NYOP and NYOP Charity, is there a difference between the proportion of purchases? Repeat steps (a)-(d) as above.

1. Visualize both Price and UnitPrice against the factor variable, Number by selecting Box-plot, and then interpret the box plots that are generated.

2. Determine the average unit purchase price for both the NYOP and the NYOP Charity conditions. Does the difference seem small or substantial? Formulate a statistical test to determine if these two average unit prices are different.

3. What are your null and alternative hypotheses?

4. Use Radiant to perform the test computation (Basics > Compare means). What can you conclude? What is the likelihood you have made either a Type I or Type II error based on your conclusion? Interpret the visualizations available on the Plot tab.

5. Use the filtering tool to investigate the difference in means for people that purchased 1 picture. Similarly, do the analysis for the group that purchased 6 pictures. Discuss what your observations.

6. If you do the analysis by hand for the group that purchased 6 pictures are your results the same as those produced in Radiant? Why or Why not?

**Economics**

1. The unit cost of making a photo is $1.20. Compute the average daily profit under each of the four pricing strategies.

2. Which strategy is the most profitable? What is the ranking of the strategies in terms of profits?

3. Now think about the additional value created by the FR Charity and NYOP Charity conditions. Rather than focusing only on profits to the theme park, let’s talk about total profits to society which should include both the theme park and the charity that benefits. What is the ranking of societal profits in this case?

4. How much additional societal profit does the leading strategy generate over the others over the entire year (assume 365 days)?

5. Are merchandise sales a concern?
