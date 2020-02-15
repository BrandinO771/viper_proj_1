# viper_proj_1
<h5>Collaborative Group Project</h5>

<h5>Participants:  Tyler Adams, Brandon Steinke, Ron Javor</h5>

<h2> Inconsistency in US Healthcare Costs: </h2>

<h5> Example: Joint replacement in the NY Manhattan area ranged from $35k to $135k.</h5>

Our team focused on medical procedure costs for Joint Replacement and Diabetes, leveraging off the consistent 2013 Medicare dataset with national standardized medical procedure codes and hospital reporting.
The data contained the average dollar amount Medicare paid to hospitals for each procedure type, the average amount hospitals charged per procedure, along with all hospitals in the country. 
<br>
<br>
After initial analysis we could see that there were sizable variance in charges for the same procedure type, not only at the national level but within same metropolitan areas. We performed a high level national analysis determining areas with some of the highest variances and then focused on all hospitals in New York, California, and Mississippi State (to get a sort of East vs West vs Middle national analysis). 
<br>
<br>
With Python Pandas we were able to extract data per state per procedure code with "loc" from the national dataset. Later we used Pandas to merge in a few other datasets of 'patient survey per hospital provider' and 'census info' per zip code joining on zip codes and provider codes respectively. We also used Pandas and the scipy library to conduct statistical linear regression T-tests looking for significant P & R values, and graphing results via MatPlotLib. We created a pandas batch method automate running all our tests per state per procedure producing summary csvs as well as seven test charts.  We tested if there were correlations between hospital charges and surrounding medium household incomes, population density, hospital rating, and patient experience. The results were mixed and differed by state. 
<br>
<br>
We were able to identify a few national correlations for cost versus population and hospital ratings. And at the state level in New York diabetes charges versus medium household income.

<h5>Our results can be viewed in this power point link.</h5>
https://github.com/BrandinO771/viper_proj_1/blob/master/_PRESENTATION/Team%20Viper%20Presentation%20Summary.docx

<h5>Medicare Data Link:</h5>
https://data.cms.gov/Medicare-Inpatient/Inpatient-Prospective-Payment-System-IPPS-Provider/97k6-zzx3
<br>
<h5>Example Charts:</h5>
<img src="https://github.com/BrandinO771/viper_proj_1/blob/master/charts/branzChartData/NY_Manhattan_Joint_Charges2.png">
<br>
<br>

<img src="https://github.com/BrandinO771/viper_proj_1/blob/master/charts/branzChartData/NY_DIABETES_Avg%20Hosp%20Charge_V_median%20Household%20Income_1.png">

 
