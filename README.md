# surfs_up
# School_District_Analysis

## Overview of the school district analysis
Due to academic dishonesty, Thomas High School ninth graders' math and reading scores were replaced by NaNs. School district files were reanalyzed to
compare the results, aiming to determine how these changes affected the overall analysis. The following analyses were covered:
1. Create data frames of district summary.
2. Create data frames of school summary.
3. Determine the top 5 and bottom 5 performing schools, based on the overall passing rate.
4. List the average math scores for each grade level from each school.
5. List the average reading scores for each grade level from each school.
6. Calculate the scores by school spending per student, by school size, and by school type

## Resources and Tools
- Data Source: [schools_complete.csv](https://github.com/CelineWW/School_District_Analysis/blob/main/Resources/schools_complete.csv),
               [students_complete.csv](https://github.com/CelineWW/School_District_Analysis/blob/main/Resources/students_complete.csv).
- Software Python 3.7.13, jupyter notebook

## Results
- **June Temperatures**
    - Original>>>>
    - Replaced>>>>
 
- **December Temperatures**
    - Original>>>>
    - Replaced>>>>
   
- **3 Differences between June and December Temperatures**
  - Highest and Lowest Temperature
     - The highest and lowest temperature in June are 85.0°F and 64.0°F. The highest and lowest temperature in June are 83.0°F and 56.0°F. Highest temperature doesn't change too much. However, midnight in December is colder than in June.
     
  - Averager Temperature 
     - The average temperature in June is 74.9°F. The average temperature in December is 71.0°F. These are very mild temperture comparing to other cities in America. Even so, June is still slightly warmer than December in Oahu island. 
  
  - Standard Deviation
    - Standard Deviation is 3.3 and 3.7 for June and December tempertures respectively. 



## Summary
After reading and math scores for the ninth grade from Thomas High School were replaced with NaNs, school district analyses results were updated. According to analyses, there were a few changes occured: 
  - The district summary: Updated average math score, passing math percentage, passing reading percentage, and overall passsing(both on math and reading) percentage are slightly lower than original ones.
  - The school summary: For Thomas High School, although average math score and reading score appear no big differences, passing math percentage, passing reading percentage, and overall passing percentage dramatically dropped. School summary for other schools were not affected.
  - School performance: Even if overall passing percentage of Thomas High School is changed from 90.948012% to 90.630324%, this doesn't affect its performance relative to other schools. Either ninth graders' math and reading scroes replaced or not, Thomas High School hold the second place of school performance based on overall passing percentage. 
  - Math and reading scores by grade: Obviously, Thomas High School 9th Graders' Average Scores were: Math-83.6, Reading-83.7. These average scores changed to NaNs. Because all the individual ninth grade student math and reading scores were replaced by NaN. 
  - For scores by school spending, school size, and school type, no changes were observed from formatted analyses data. 
  
 *Notice: Since all dataframe were formatted to certain decimals places. The changes of analyses results are based on current formatted data. If trace back to original data or formatted to more decimal places, there might be delicate changes been noticed.*
