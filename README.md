# School_District_Analysis

## Project Overview

This project was brought on as a request for further insights into the performance of schools in the Py City District based on current records of both school metrics and student metrics.

### Purpose

  The purpose of this analysis was to link the school data with the student data to find any link between metrics such as school size and school spending with the success rate of an individual student. This analysis can provide insights that will allow for the future planning of additional funds or potential restructurings that can maximize the success rate of the student. 
  
  The secondary purpose of this analysis was to eliminate the overarching effects of suspected loss of grade integrity, potentially occurring in the Thomas High School ninth grade data.  The effects on the district and school summaries were reanalyzed to account for this potential discrepancy.
  
  ### Effects on the School District Summary
  
  The district Summary was affected in a couple of ways, but none that seem to be of a major consequence. This is of course pending the application to rigorously adhered to funding programs where a one or a tenth of a percent, in a given metric, could be the deciding factor in grant approval. The differences in the District Analysis results with and without, respectively, the 9th grade scores from Thomas High School (THS) can seen in the two figures below.
  
#### School District Summary With THS 9th Graders

![District Summary with THS Ninth Graders](https://github.com/Beardlow/School_District_Analysis/blob/main/district_with_THS.png)

#### School District Summary Without THS 9th Graders

![District Summary Without THS Ninth Graders](https://github.com/Beardlow/School_District_Analysis/blob/main/district_without_THS.png)

### Effects on the THS School Summary

  The effects of removing the THS ninth graders are only seen in the THS school summary. The effects on the overall passing percentages do not seem to be very dramatic with all of the passing percentages without the ninth graders being within one percent of the passing percentages with the ninth graders. If there was academic dishonesty it was not to a very large extent, albeit still serious. The THS school summaries with and without the ninth graders are below.
  
#### THS Summary with Ninth Graders
  
![THS Summary with Ninth Graders](https://github.com/Beardlow/School_District_Analysis/blob/main/ths_w_ninth_graders.png)
  
#### THS Summary without Ninth Graders
  
![THS Summary without Ninth Graders](https://github.com/Beardlow/School_District_Analysis/blob/main/ths_wo_ninth_graders.png)
  
#### THS In-District Comparisons After Removing Ninth Graders

#### THS District Ranking With and Without Ninth Graders
  
    Thomas High School's status of being 2nd place, after removing their ninth graders, with regards to Overall Passing Percentages, remains in tact. Luckily this did not change the Top Schools List so no restructuring based off of this list is needed.
    
#### THS Reading and Math Scores Without Ninth Graders
  
    The only change that occurred to the by school and by grade summaries was that the math and reading scores for THS, with regards to the ninth grade, was that this value was replaced with a null, on NaN, result. The effect on the math scores for THS can be seen below.
    
#### NaN in THS Ninth Grade Math Results
  
![THS Grade Summary without Ninth Graders](https://github.com/Beardlow/School_District_Analysis/blob/main/math_scores_by_grade_wo_THS_ninth_graders.png)
  
#### Effects on Passing Percentages by Spending Range
  
    The effects of removing the THS ninth graders on the passing percentages per spending range are very miniscule. They cannot even be detected at the .1% level of resolution that we are using. The results for passing percentages per spending range are below.
    
![Spending Ranges Results](https://github.com/Beardlow/School_District_Analysis/blob/main/Results_by_Spending.png)
  
#### Effects on Passing Percentages by School Size
  
    The effects on passing percentages per school size remains unchanged at the .1% resolution level. The results are in the image below.
 
![School Size Results](https://github.com/Beardlow/School_District_Analysis/blob/main/school_size_results.png) 
 
#### Effects on Passing Percentages by School Type

  The effects of removing the THS ninth gradders on the passing percentage by school type are undetectable at the .1% resolution level. The passing percentages by school type are below.
  
![School Type Results](https://github.com/Beardlow/School_District_Analysis/blob/main/School_type_results.png) 

## Analysis Summary
  
  This analysis shows that even though the Thomas High School ninth graders were removed, the effects on the District and the By School summaries remain relatively unchanged. The changes in the analysis results are almost all related to THS specifically.
  
  Markup : *Changes Seen
              *THS overall math passing percentages were reduced by .1%
              *THS overall reading passing percentages were reduced by .3%
              *THS overall Passing Percentage was reduced by .3%
              *THS average reading scores were increased by .05%
              *THS average math scores were reduced by .06%
  
