# School District Analysis

## Overview Analysis School District 

The school district has requested a preview of different key metrics by school campus and refined by district level.
With this perspective the following project intend to show a clear analysis focused on Math performance and Reading scores disassembling several different ways for display data in order to help on decisions for the upcoming board meeting. After a deeper look into the data the school board have requested more information on Thomas High School specifically for the 9th grade once there was some doubt about legitimacy of grades. Further on the data was separated and investigated in different perspectives.

## Results

#### District Summary Repercussion 

In order to have a closer look to verify and assure the grades scores for 9th grades, the data was cleaned after identifying null data information, from that it was compared the metric of percentages of math grades passing, reading passing and overall passing. 
As we can observe on the charts below when comparing the data, we had pull 461 tests that had null data. From this information we can assume that the difference before the data changes was minimum, representing less than 1% of the totals.

Original data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/original_01.png" width="700">

Adjusted data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/adjusted_01.png" width="700">



#### School Summary Repercussion

After exanimating the original data, the Thomas High School was placed at 91% overall passing rate, which raised some doubts about the legitimacy of the data information. Further on the total number of 10th and 12th graders was redirected as denominator and the data was adjusted.
On the charts below we can see that removing the 9th grade students the data set had change considerably, with a descending overall passage from 91% to 65%.

Original data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Original_02-.png" width="700">

Adjusted data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Ajusted_02.png" width="700">

#### How replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools

The first analysis shows Thomas High School ranked 2nd in the district. What made the board request more information and details on this data, suspecting the veracity of information.
After adjusting the 9th grade data, Thomas High School ranked at 8th place.

Original data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Original_03--.png" width="700">

Adjusted data
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Adjusted_03.png" width="700">

#### How does replacing the ninth-grade scores affect the Math and reading scores by grade

On this part of the analysis, we can determine that the data replacement did not change the math and reading scores by grade. As we can observe that on the summary for Thomas High School the amount displayed as “nan” in both charts.

Math scores
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Original_04.png" width="249">

Reading scores
<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Adjusted_04.png" width="250">

#### How does replacing the ninth-grade scores affect the Scores by school spending

Facing the School spending summary, we can conclude that the data modifications did not have a big impact on the spending ranges for the average math scores or average reading score. We can notice that Thomas High School is on the overall range of $630-644.

<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Spending_range.png" width="700">

#### How does replacing the ninth-grade scores affect the Scores by school size
	
It was discovered with that the Average Scores and Passing Percentages do not increase as spending per student increases. However, the top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). What leads us to believe that there are more relevant factors than funding that decide average student scores.

<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/School_size.png" width="700">

#### How does replacing the ninth-grade scores affect the Scores by school type

With the information gathered we can assume that the Charter schools performed better than District schools. The top five schools with the highest overall passing percentages are all Charter schools, on the opposite side at the bottom five are all District Schools. Concluding that Charter schools in this analysis were typically characterized as "Small" and "Medium" size schools and have a 36% higher overall passing percentage than District schools.

<img src="https://github.com/abramscris/School_District_Analysis-/blob/main/Resources/Scoreby_type.png" width="700">

## Summary
As in conclusion of this project after updated data that originate for the initial requested changes in the categories reading and math scores for the ninth grade at Thomas High School, on the process of replace null students per Nans it was obtained the following modifications on data frame. The overall passing rate for Thomas High School changed considerably from 91% to 65% and when ranked after the updated Thomas High School dropped from 2nd to 8th place on district analysis,
When pulling the 9th graders students, Thomas High School will have Nan in reports as a result of alterations and as a final note the district as whole has also average math and reading scores decreased.
Unfortunately, with the small variation of changes found on this analysis, we cannot assure that the numbers for reading and math at Thomas School are false or dishonest. Possibly with more profound analysis from this specific school and with a larger data base analysis we can possibly find discrepancies.
