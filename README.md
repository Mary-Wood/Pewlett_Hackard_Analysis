# Pewlett_Hackard_Analysis
This is a project using SQL to analyze employee data to find out the number of employees that will be retiring soon. 

## Overview

The original analysis examined the number of employees born between 1952 and 1955 and those who were hired between 1985 - 1988 to determine who was was likely to retire in the near future. We also created csv files with this data to determine of these potential retirees, what departments they were in and their manager names. However, due to the nature of this analysis there were multiple instances of a single employee for each job title they had held while at the company. 

The purpose of this secondary analysis was to parse out each employee and their last held job title. Files were made that presented data showing the current job title for the group of potential retirees, the total number of people with each job title that were in the retiring range to best plan for transition, and finally to further examine which employees would be best to act as mentors due to being several years out from retirement. 

## Results

* There are 90,398 total employees near or in their retirement age. 
*  The breakdown of these employees near or at their retirement age, shows that departments of Engineering and Staff will need to be prepared for the changes that may occur due to these retirements. These would be the ideal candidate groups for the mentorship program. ![Count of Retirees Per Job Title](https://github.com/Mary-Wood/Pewlett_Hackard_Analysis/blob/main/Count%20of%20mentors%20per%20job%20title.png)
* There were 1549 employees selected, due to being several years out from retirement, as ideal candidates for the mentorship program. 
* The breakdown of these employees that were ideal candidates shows that they did represent the categories needed most, engineering and staff. ![Count of Retirees Per Job Title](https://github.com/Mary-Wood/Pewlett_Hackard_Analysis/blob/main/Count%20of%20retirees%20per%20job%20title.png)

## Summary

* This additional analysis provided insights into the number of employees expected to retire soon, and their roles. This information will allow for preparation for these staffing changes to best ensure the success of the company. Mentors were selected by birth age to be several years out from retirement. These employees were also in the departments that would experience the greatest loss of staff. 

* This analysis did originally include counts of the job titles of the employees that would be retiring soon. However, it did not include counts of the job titles of the employees selected for the mentorship program. This meant that while it was possible to extract each individual employee, the big picture was still unclear. As such I asked the following question: Does the selection of job titles of these mentors accurately represent the same titles of the employees soon retiring? That simple count (seen above) provides this information. At a top level glance, these job titles appear to be in similar groups. 

* A second question that this analysis did not attempt to answer was what the trends were for employees that had already retired. While there may be general expected ages for retirement, individual trends may exist further by job title or location. 
This could further prepare the company for the specific experience that they could expect as this group of employees neared retirement. 
