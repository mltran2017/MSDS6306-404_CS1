##CODEBOOK.md
This contains the file structure and objects/variables that are in this project.

##README.md
Contains a brief description of the project.

## pres/
A folder containing the presentations for this project.

## pres/ZGill_CaseStudy1_Pres2.ppt
Zackary Gill's powerpoint presentation. At the end of the slides is the link to the YouTube video.

## pres/6306_CaseStudy_1_Slides.ppt
The presentation slide deck.

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
The HTML output from knitting the 6306_CaseStudy_1.rmd file.

## 6306_CaseStudy_1.rmd
### Objects
**_beers_**		The raw Beers.csv input

**_brew_**		The raw Breweries.csv input

**_numBrewPerState_**	A data frame of the number of breweries per state

**_beers2_**		A temporary object equivalent to 'beers' with the columns renamed for merging

**_df_**		The resulting dataframe from merging 'beers2' and 'brew'

**_naPer_**		The number of NA's per column

**_group_**		A data frame of the medians of 'df$IBU' and 'df$ABV' by 'df$State'

**_max.abv_**	The state that contains the maximum ABV value

**_max.ibu_**	The state that contains the maximum IBU value

**_maxvals_**	Merges 'max.abv' and 'max.ibu'

**_sumABV_**	The raw summary of 'df$ABV'

**_sumABV1_**	sumABV converted to a data frame
