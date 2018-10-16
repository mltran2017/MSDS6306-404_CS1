# MSDS6306-404_CS1
This is a probject analyzing the provided datasets (Beers.csv and Breweries.csv) which contain two lists of 2410 US craft beers across 558 US breweries.

## csv/
This folder contains the .csv files that are use in the 6306_CaseStudy_1.rmd file.

## csv/Beers.csv
The beer dataset.

## csv/Breweries.csv
The brewery dataset.

## instructions/
This folder contains the instructions for this assignment

## instructions/Case Study 01.docx
The instructions for this probject.

## instructions/CaseStudy1Rubric.docx
The grading rubric for this probject.

## 6306_CaseStudy_1.html
The output from knitting the 6306_CaseStudy_1.rmd file.

## 6306_CaseStudy_1.rmd
### Objects
**_beers_**		The raw Beers.csv input.

**_brew_**		The raw Breweries.csv input.

**_numBrewPerState_**	A data frame of the number of breweries per state

**_beers2_**		A temporary object equivelent to 'beers' with the columns renamed for merging

**_df_**		The resulting dataframe from merging 'beers2' and 'brew'

**_naPer_**		The number of NA's per column

**_group_**		A data frame of the medians of 'df$IBU' and 'df$ABV' by 'df$State'

**_max.abv_**	The state that contains the maximum ABV value

**_max.ibu_**	The state that contains the maximum IBU value

**_maxvals_**	Merges 'max.abv' and 'max.ibu'

**_sumABV_**	The raw summary of 'df$ABV'

**_sumABV1_**	sumABV converted to a data frame
