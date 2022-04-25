# School District Analysis

## Overview of the school district analysis

This analysis is intended to inform the School board and the Superintendent about trends and patterns in the behavior of various key variables for decision-making regarding budget planning and school priorities at the local and district levels.
Previously, a first report was delivered with the description of the available information from which it was concluded that the file showed evidence of academic dishonesty; specifically, the reading and math scores for Thomas High School's ninth graders appear to have been tampered with.
To maintain state testing standards, the decision was made to do again the analysis, replacing Thomas High School's math and reading scores with NaNs while keeping the rest of the data intact and asking us to describe how these changes affect the overall analysis. BootCamp TDM- VIRT-DATA-PT

## Results:

When we change the data for the math and reading scores of Thomas High School's ninth graders without changing or deleting anything else, we can see a table like the following:

### Table 1. Student data without the ninth graders scores of Thomas High School

![Student data without the ninth graders scores of Thomas High School](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/student%20data%20without%20the%20ninth%20graders%20scores%20of%20Thomas%20High%20School.png)

This way we are sure to be able to work with the right information.
Let's remember that one of the options for handling information with Missing Data is Do nothing, which is precisely what we were asked to do in this new analysis: fill in the scores keeping the rest intact.
According to Handle Missing Data:Bootcamp TDM-VIRT-DATA-PT-03-2022-U-B-TTH if we do nothing when we sum or take averages of the math or average scores, those NaNs will not be considered in the sum or the averages. Thus in this case the missing data have no impact.
The foregoing means that there should not be much impact on our general results, only on those related to the scores because we did have data that was considered in the previous report. Let's see what was found.

How is the district summary affected?

In the district summary comparison table below, it can be seen that the totals did not change as expected. While the averages and percentages do show a slight decimal difference. This is because we have omitted information with the missing data applied.
However, the impact is not significant.

### Table 2. District Summary Comparison
![District Summary Comparison](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/District%20Summary%20Comparison.png)

How is the school summary affected?
How does replacing the ninth graders math and reading scores affect Thomas High School’s performance relative to the other schools?

On the other hand, when we do the analysis by school (see school summary comparison table) it can be seen that only the information related to the scores of Thomas High School has changed, the other schools remain the same.
The changes observed in the new averages and percentages are very small (the overall average with missing data is 90.630324 compared to 90.948012 in the previous analysis, that is -0.317688), so Thomas High School continues to hold second place in the top five performing schools based on the overall passing rate.
Thus the Thomas High School's performance relative to the other schools did not change.

### Table 3. School Summary Comparison
![School Summary Comparison](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/School%20Summary%20Comparison.png)

### Chart 1. Overall Passing School Comparison Chart
![Overall Passing school comparison Chart](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Overall%20Passing%20school%20comparison%20chart.png)


The above information reveals that there is not much impact of omitting the 9th grade grades, which means that it is very likely that there is not some kind of dishonesty on this side.

### Chart 2. Overall Passing Chart
![Overall Passing Chart](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Overall%20Passing%20Chart%20.png)
How does replacing the ninth-grade scores affect the following:

* Math and reading scores by grade

Regarding the math and reading scores by grade we can see at the comparative tables that the only data that changes is the ninth grade for both scores and only for Thomas High School.

### Table 4. Math Scores by Grade

![Math Scores by Grade](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Math%20Scores%20by%20grade%20comparison.png)

### Table 5. Reading Scores by Grade
![Reading Scores by Grade](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Reading%20Scores%20by%20grade%20comparison.png)

The output obtained is a missing data for both scores but this behavior was expected because we have omitted this information.
It is due to that according to Missing Data: Bootcamp TDM-VIRT-DATA-PT-03-2022-U-B-TTH if we multiply or divide with a row that has a NaN, the answer will be NaN.

* Scores by school spending
Because changes in the average Math and reading scores were minimal after omission of data for the Thomas High School ninth-grade scores, the Score by School spending did not change.

### Table 6. Scores by school spending
![Scores by school spending](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Scores%20by%20School%20Spending.png)

* Scores by school size and Type

In general, the results for the Scores by School Size and Type are not affected either for the same reason as before, that the changes due to missing data were really very low.

### Table 7. Scores by school size
![Scores by school size](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Scores%20by%20School%20Size.png)
### Table 8. Scores by school type
![Scores by school type](https://github.com/LAURYMEOW/School_District_Analysis/blob/main/Scores%20by%20School%20Type.png)

With the above, it is concluded that an evaluation of the information through the method of handle missing data with the option do nothing allows us to see if there really is inconsistency in the information of the Thomas High School ninth graders.
According to the information received and the results obtained, the suspicion is not revealing and therefore not certain.  
