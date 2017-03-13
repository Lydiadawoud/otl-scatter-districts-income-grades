otl-scatter-district-income-grades
===================
CT school district income and grade levels 2009-13 in Highcharts scatter chart

## live link
https://jackdougherty.github.io/otl-scatter-district-income-grades/index.html

## created for OnTheLine book
- http://ontheline.trincoll.edu

## license
http://www.highcharts.com is free for personal websites, school sites, or non-profit organizations. Commercial use requires the purchase of a license.

## credits
- Thanks @ilyankou for seriesMapping data, tooltips, and improving overall code
- Thanks @andrewbtran at http://TrendCT.org for function to display financial data (with $ and commas)

## learn more at DataVizForAll.org
- Tutorial: Modify and Host a Highcharts Scatter Chart Template on GitHub, https://www.datavizforall.org/github/fork-highcharts
- More Highcharts Templates, https://www.datavizforall.org/Highcharts

## data
- Sources: Stanford Education Data Archives, TrendCT, ACS 2009-13			
- Andrew Ba Tran, “Wealth and Grades: Compare Connecticut’s School Districts,” TrendCT, May 6, 2016, http://trendct.org/2016/05/06/wealth-and-grades-compare-connecticuts-school-districts/.			
- TrendCT data repository, https://github.com/trendct-data/stanford-cepa			
- based on Motoko Rich, Amanda Cox, and Matthew Bloch, “Money, Race and Success: How Your School District Compares,” The New York Times, April 29, 2016, http://www.nytimes.com/interactive/2016/04/29/upshot/money-race-and-success-how-your-school-district-compares.html		
- based on Sean F. Reardon, Demetra Kalogrides, Andrew Ho, Ben Shear, Kenneth Shores, Erin Fahle. (2016). Stanford Education Data Archive, (Version 1.1 File Title), http://purl.stanford.edu/db586ns4974
- Median Household Income, Table 57, American Community Survey 2009-13, from Social Explorer, http://www.socialexplorer.com/tables/ACS2013_5yr

## definitions
- grade levels SEDA = average of 6th grade English and Math scores on CT tests, linked to NAEP test scores, and expressed as "grade level equivalents" (above or below national average), from TrendCT data repository, based on New York Times analysis of Stanford Education Data Archive data			
- median household income (MedHIncACS200913) = American Community Survey 2009-13, used here instead of SEDA median family income calculation below. For CT regional school districts, which are comprised of two or more rural towns, I calculated the average of median household incomes for all towns, with no weighting for student enrollment
- median family income calculation by SEDA, labeled inc50all = income at 50th percentile (all)	SDDS/ACS	percentiles computed by interpolating over counts of people in each of 16 income categories. But I did not use this because it was not equivalent to ACS 2009-13 town-level median family income or median household income, or any other easy-to-replicate measure in ACS 		
- Correlation coefficients (between various income measures and SEDA grade levels)
  - MedHIncACS200913 = 0.777967328 = used in this analysis, although other values are higher
  - MedFIncACS200913 = 0.947981875
	- median family income SEDA = 0.799337334
