# School_District_Analysis
## Panda Module Challenge, School District Analysis
 ### 1. Overview of the school district analysis: Explain the purpose of this analysis.
The purpose of the school district analysis was to assist the decision making of a city school board. We were tasked with analysing standardized testing data along with other relevant data to make this information usable by the school board.

### 2. Results: Using bulleted lists and images of DataFrames as support, address the following questions.

**How is the district summary affected?**
- Removing the 9th grade students from Thomas High School did not significantly change the outcomes of the district summary. The average math score dropped from 79% to 78.9 %. The average reading score stayed put at 81.9%. The percentage of students that passed math sunk by .2% from 75% to   74.8%. The largest change was in reading, which shifted from 86% to 85.7%. The overall passing percent lowered from to 65% to 64.9%. Eliminating a single grade from one of the fifteen schools proved to have minimal effects on the district level.

**How is the school summary affected?**
- When you originally take out the 9th grade scores the rates bottom out, because at that point the divisor is the original student count. Once the percentage is calculated using the correct number of students, the averages normalize to a number quite similar to the original value. All of the Thomas High School passing percentage values shifted, but by less than a percentage point. 

**How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?**
- Thomas High Schools ranking stayed the same relative to their peers. There was a miniscule shift in their averages, but they kept Second Place in the school rankings by Overall Passing Percentage. Griffin High School narrowed the gap, but did not pass Thomas High School in the end. It is notable that both of Griffin High School's "Passing Math" and "Passing Reading" percentages are higher than Thomas High School, yet the "Overall Passing" percentage is still slightly lower. This tells us that Griffin High School has more students that passed either math or reading, but not both.

### How does replacing the ninth-grade scores affect the following:

**Math and Reading Scores by Grade**
- The reading and math "by grade" data frames are changed, but only in the rows for Thomas High School. Ninth grade for Thomas High School shows "nan" to represent the null values. 

**Scores by School Spending**
- When formatted to round to the the nearest .1% the scores by school spending stayed exactly the same.

**Scores by School Size**
- Scores sorted by school size also stayed the same when rounded. The overall passing percentage for the large school type is notable because it is startlingly lower than its counterparts.

**Scores by School Type.**
- Scores by school type was another dataframe that stayed exactly the same after being rounded. 

### 3. Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- Overall, there was very little change in the analysis. At the district level, the average math and percentage math scores both drooped slightly. Interestingly, the district reading score average stayed the same, but the percentage that passsed actually dropped a bit. In the school summary, Thomas High's average passing percentages shifted subtly. The Thomas High School Passing Math Percentage dropped just a bit, from 93.272% to 93.186%. Passing Reading Percentage and Overall Passing Percentage, at Thomas High, also dropped slightly. When looking at the "By Grade Analysis" you notice the Thomas High School 9th Grade numbers are replaced with "nan". It's good to have a dataframe free of the potentally compromised information, but in the end it would not have changed the takeaways much at all.
