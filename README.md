# Analysis of Rocket Fuel Ads Experiment Results by Subgroups
The case “Rocket Fuel: Measuring the Effectiveness of Online Advertising” is available for purchasing from the Harvard Business School case pack.  
  
For the analysis we are going to break down results by sub-groups depending on the number of times the individual was targeted for ads (tot_impr). I have created a data set called rocketfuel_deciles that you can use for this purpose. This simply takes the original rocketfuel data and adds a column labeling people into deciles (i.e., 10% groups) by tot_impr. (Note that when there are ties, different programs may break ties to put people into deciles differently. So my deciles won’t necessarily match yours, but should be similar).   
### This experimental analysis follows the logic below:  
1. Generate summary statistics for variables in the data.    
2. Create a table to show the numbers and shares of individuals who were in the treatment vs. control group.   
3. Create a table of means and standard deviations and also graph histograms to check for balance in the variables that should not be affected by treatment across treatment and control.  
4. Plot the means and confidence intervals of the main outcome “converted” by control and treatment. Interpret the result and give a brief description of the confidence intervals, including noting whether one group has a higher or lower CI and whether that makes sense.   
5. Calculate and report the estimate of the Average Treatment Effect (ATE) of the ads for treatment relative to control, the associated standard error, and provide a 95% confidence interval on the Average Treatment Effects.   
6. Calculate the ATE again using the regression approach based on heteroskedasticy robust standard errors. Compare the results with the results in Q7.  
7. Create a summary table showing the sample size, the mean and the standard deviation of variables in the data set for both treatment and control group over the 10 deciles of total impressions.  
8. Finally create a graph that shows the mean and 95% CI on “converted” separately for treatment and control plotted over the 10 deciles of total impressions.  
