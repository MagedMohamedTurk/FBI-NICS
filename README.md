# FBI-NICS
In this dataset investigation, data cleaning and wrangling were done and descriptive stats were applied to find correlations
## Conclusions
* Trend of `gun registration` shows some positive correlation with some `life threatening events` in state Louisiana and Texas (2005-2006 during `hurricane Katrina` and 2012 `The Sandy Hook school shooting`<br> <a href="#Q5">as discussed in Q5</a> and also seen in 9/11 event. 
* There is a positive correlation between the percent of `White population percent` in a state and the `registered guns per capita` in this state based upon statistics 2016 <br> <a href="#Q6">as discussed in Q6</a><br>
* In the majority of months, the registeration did not exceed 100,000. <a href="#Q7">as discussed in Q7</a><br>


<b> Notes:</b><span style="color:red">(Resubmission Note)</span><br>
The above conclusions were limited by the followings:<br>
1. Guns registration data file:
  * We can't be certain that the number of guns registered is the same as the ones sold as per Harvard study ___[here](https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md)__ .
> A forthcoming study conducted by Harvard researchers found that roughly <b>40 percent</b> of respondents had acquired their most recent firearm <b><u>without</u></b> going through a background check.
  * The Data file contained information about 55 states(with non-official 5 states) . I omitted those data to match `census` dataframe.



2. Census Data:
  * <b><u>Only year 2016</u></b> was analysed. This is because it was the year that only carried some complete data about the race's percentage. Further investigation of other years and going through some other important factors like non-employment, income per capita, persons per square feet could make the conclusions more precise.
  * All footnotes were eliminated to get numerical data.
  * Data file was not consistent about expressing the percentage, sometimes with the symbol `%` and sometimes with decimal point. This was overcomed by data manipulation but it can affect the accuracy of the data.
 
