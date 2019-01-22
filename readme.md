# Prosper Loans - Data Visualization
## by Ernest Rowe


#### Dataset: [Loan Data from Prosper](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1546576456543000)
_**Additional data from:** [census.gov](https://www2.census.gov/programs-surveys/popest/datasets/2010-2018/national/totals/nst-est2018-alldata.csv)_

This dataset contains 113,937 loans with 81 variables, including loan amount, borrower interest rate, current loan status, borrower income, and many others. More information on the variables in this dataset can be found [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1546576456544000).


## Summary of Findings

Prosper Loans saw massive shifts in their lending over the 10 year period in the dataset. Nearly every feature I looked at had some effect on my features of interest (loan amount, interest rate, & geographic distribution), but the relationships I chose to explore in more depth alongside loan amount & interest rate, were credit score, loan term, & origination year. Those with high credit scores were eligible for higher loan amounts & also benefited from lower interest rates. Their higher score also gave them access to loan products (1 Year & 5 Year loans) that weren't open to low credit individuals. Plotting the number of loans originated in each month showed just how hard the economy was hit in 2008-2009. Prosper actually stopped originating completely from October 2008 to May 2009 and when they came back, they were only originating a couple loans per month until August.


## Key Insights for Presentation

The greatest insights gained from the presentation were from plotting loan amount & interest rate against categorical variables. The use of violin plots & a log transformation on loan amount uncovered the major differences between loans of different terms. Borrowers with a 1 Year loan enjoy lower interest rates, but their maximum loan amount was capped at $25,000. 3 & 5 year terms both go as high as $35,000, but neither of them have the low interest rates you see with 1 year loans. Paying attention to the interquartile ranges, you can see that almost all of the people taking out 5 year loans do so for large loan amounts. Grouping by OriginationYear, I was able to see that Prosper raised their minimum loan amount from $1,000 to $2,000 in 2011, and they boosted their maximum loan amount from $25,000 to $35,000 in 2013.

##### Resources:
https://census.gov
https://classroom.udacity.com
https://stackoverflow.com/
https://stackexchange.com/
http://seaborn.pydata.org
http://youtube.com
https://plot.ly
http://reddit.com
http://www.damian.oquanta.info/posts/hide-the-input-cells-from-your-ipython-slides.html
