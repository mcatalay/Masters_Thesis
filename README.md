# Masters_Thesis
My master's thesis form as of June 2020, Submitted and received a grade of A. 

## Abstract

Using variation in the political affiliations of firms listed in the Istanbul stock exchange and the 2016 failed coup attempt in Turkey as a exogenous political shock, we find that politically connected firms (both with the government and the coup-plotters) were associated with more negative stock returns relative to politically unaffiliated firms during political and policy shocks. We find that these political affiliations are persistent both in the past and in the future. In the context of the Gezi Park Protests of 2013, we show that they interact with social unrest and social media to affect stock returns. These results suggest that politically connected firms may have a valuation premium due to their political connections. In addition, if a firm is perceived as a threat by the government, its valuation may suffer additional losses.

## Code Content

All code in `R`, in the form of `Rmarkdown` files. 

`Deneme2.Rmd`: Runs regression for December 17th Corruption Scandal, creates LaTex output and histogram plot

`Deneme5.Rmd`: Runs regression (regular and clustered errors) for Gezi Park Protests on selected days of events with Tweets, creates LaTex output

`Gezi_data.Rmd`: Merging and wrangling 3 datasets (financial information on firms, daily twitter activity, protest and repressions activity), runs regressions with different combinations of variables, creates LaTex output, contains code to produce Tree Regression diagrams during Gezi Park Protests

`Gezi_data_tusiad_tables.Rmd`: Same as `Gezi_data.Rmd` but now Pro-Fetullah firms as base-case in political affiliation dummy variable in regressions. (output not included in Thesis)

`Tablelar.Rmd`: Runs regression regression on Gezi Park Protests, balance of payment crisis, Istanbul municipal elections and during the early stages of Covid-19, creates LaTex output

`Tez_data_compile.Rmd`: Code for combimining balance sheet `.csv` files for top 110 public traded companies by market valuation in the Istanbul stock market. 



