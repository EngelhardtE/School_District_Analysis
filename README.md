# School_District_Analysis

## Overview

In order to perform a district wide analysis, grade data was gathered from the relevant schools. However, it was revealed that the data on Thomas high School's ninth graders was illegitimate. Therefore, all of the grade data on those specific students was changed to null values and the analysis was performed a second time disregarding THS's ninth grade class. Changes in the results from before and after the revelation were then compared to determine the effects of the change. 

## Results

- Changing Thomas High School's ninth grade data has no effect on the district summary, as only about 1% of the overall data was altered. 
- The School Summary is exactly the same except for Thomas High School's pass rates slightly changing. Their math pass percentage changed from 93.27% to 93.19%, and their reading pass percentage changed from 97.31% to 97.02%. Finally, their overall pass percentage changed from 90.95% to 90.63%. 
- Although their grade averages shifted due to the change, Thomas High School remained in the same grade ranking positions when compared to other district schools. They are still ranked second in the district for overall passing percentage; however, it should be noted that the gap between them and the #1 school (Cabrera High School) has widened. 
- Math and reading scores by grade were only affected in that Thomas High School no longer has data under the ninth-grade portion of both the math and reading dataframes.
- Scores by School Spending, School Size, and School Type did not see significant changes. This is likely due to only a small percentage of the overall data being changed (roughly 1%). 

## Summary
Although much of the school district analysis was largely unchanged by the correction in the grade data, there were some key differences between the flawed data analysis and the final product. Firstly, Thomas High School saw a slight dip in their math pass rate of 0.08%. Furthermore, their reading pass rate slightly decreased by 0.29%. Both of these shifts factor into the decrease in their overall pass rate decreasing by 0.32%. It should be noted that even with these changes, Thomas High School's district rankings stayed the same (#2 overall, #2 in reading pass rate, and #7 in math pass rate). Finally, Thomas High School was knocked out of the "by grade" analysis' ninth-grade portion, as their relevant data was deemed illegitimate. 
