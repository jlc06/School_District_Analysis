# School District Analysis

## Project Overview
While helping Maria, the chief data scientist of a city school district, prepare and report on data trends, we were notifed by the school board that the initial data file we were working with had compromised data. We were told the 9th grade reading and math scores at Thomas High School showed signs of being altered and needed to be omitted in our analysis. To ensure the testing standards for the school district were upheld and any policy decisions were made without using inaccurate data, I stripped out the 9th grade scores from Thomas High School and repeated the analysis Maria and I had initially run. 

## Results
Following the cleansing of the data to omit all math and reading grades from the 9th graders at Thomas High School, here is how the summary tables changed:
- District Summary:
  - The average math score dropped from a 79 to 78.9
  - The average reading score remained the same (81.9)
  - The % passing math dropped from 75% to 74.8%
  - The % passing reading dropped from 85.8% to 85.7%
  - The % passing overall dropped from 65.2% to 64.9%
- School Summary:
  - The school summary is unaffected other than Thomas High School's metrics (please see below)
- Thomas High School:
  - The average math score dropped from 83.42 to 83.35
  - The average reading score increased from 83.85 to 83.90
  - The % passing math dropped from 93.27 to 93.19
  - The % passing reading dropped from 97.31 to 97.02
  - The % passing overall dropped from 90.95 to 90.63
- Math and Reading Scores by Grade
  - This summary is unaffected other than the Thomas High School 9th grade scores being empty (NaN)
- Scores by Spending:
 - The "$631-645" grouping had minimal changes, but when rounding to the nearest 10th place or whole integer were insignificant
- Scores by Size
 - The "Medium" school grouping had minimal changes, but when rounding to the nearest 10th place or whole integer were insignificant
- Scores by Type
  - The "Charter" school grouping had minimal changes, but when rounding to the nearest 10th place or whole integer were insignificant
## Summary
After we omitted the reading and math scores from the 9th graders at Thomas High School, there were changes (mostly minimal) seen in the following:
  1. After initally removing the 9th grade Thomas High School data, the % passing math, reading, and overall metrics dropped significantly due to a large denominator under a now significantly smaller numerator. To remedy this, we calculated a new denominator (removing the number of Thomas High School 9th graders) for both the overall grades at the district level and the Thomas High School metrics. After including this new denomintor, the percentages dropped, but only minimally (please see above).
  2. 
