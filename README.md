# Data-Madness

**Important Note:** The data that was retrieved from Numbeo's API can be found in the JSON_files.rar folder. The API key will only be valid until 27/03/21 which means that retrieving the data directly from the notebook after that date will not be possible anymore.

## Short Project Description

The objective of the project is to determine the best country to live in as a freshly graduated Data Science student when looking at a diverse range of requirements from best average salary and purchasing power to the quality of life at the different canditate destinations. The analysis follows the narrative of Eve, an ambitious young data scientist.

### Analysis Outline
A rough outline of the analysis steps and techniques used:

+ We aggregate data from Kaggle's ML and Data Science Surveys as well as Brent Ozar's Data Professional Salary Surveys from the years 2017-2019 in order to get a large underlying dataset with a diverse population of data professionals. The challenge is to make the data compatible.
+ We construct and employ data to perform tax wedge adjustment. 
+ We construct dataframes by calling the Numbeo API and use that data to enrich our analysis.
+ We perform Hypothesis Testing regarding the influence of the gender on salary for data professionals which yields interesting results.
+ We look into whether pursuing a Masters degree is actually worth it from a monetary perspective and investigate whether that differs from country to country.
+ Last but not least we provide an informed advice on which country(ies) might be worth looking into if you plan to relocate.

