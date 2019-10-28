# School_District_Analysis_ppd
M4/District Analysis w/ Pandas &amp; Jupyter

## District summary implications
The effect of removing of removing the Thomas HS 9th grade math and reading scores has a very minor impact on the results, in particular the Math, Reading and Overall Passing percentage. Math Passing rate dropped from 75% to 74%, Reading dropped from 86% to 85% and Overall rates dropped from 80% to 79%. While a drop is to be expected since a portion of students is being removed from passing consideration, though not removed entirely, the impact is minor, and unsurprisingly so. Bear in mind that with four grades and fifteen schools, the Thomas HS ninth grade represents ~1.6% even without considering the variety in class size. 

## School summary implications
With the Thomas HS 9th grade scores in question, their place in the school summary is completely different. Prior to the allegations of academic dishonesty, Thomas was one of the top performing schools. During the current investigation, all Thomas 9th graders’ scores are held as “non-grades”. As a result, the Thomas HS student body population (denominator) remains static, but roughly 25% of the school’s student body (numerator) has non-grades in both math and reading. As a result, through the lens of passing grades > 70 and everything else is non-passing, these Thomas 9th graders are categorized as non-passing. Some of those ninth graders had non-passing grades prior to the discovery, however, the temporary removal of 20-25% of the passing grades at Thomas HS has pushed the school’s standing to the bottom third in the rankings.  

## Effects on Thomas High School's performance relative to other schools due to removal if ninth graders’ math and reading scores
The removal of the Thomas 9th graders’ scores adversely affects the school’s ranking in the district. Prior to the academic integrity allegations, Thomas HS was a top ranked reading school in the district and 7th in math. With the new rankings that don’t consider the Thomas 9th graders, the schools ranking in reading drops to last (15th) and the math scores drop two spots to 9th. 
The two subject matter tables are interesting and provide food for additional consideration. The reading passing percentage table has roughly half (8/15) schools scoring in the “A” range (>90%) and the balance (7/15) bunched around B-/C+ range. After the Thomas HS “scandal”, the bunching is virtually the same except there is one fewer “A” school (7/15), the same number of B-/C+ schools (7/15) and one “C-/D” school (Thomas HS). 
The math reading passing % is similar to a degree. Roughly half (8/15) are “A” grade schools but the next bunching (7/15)  is solidly “D” schools. While Thomas didn’t drop too far in the rankings (7th to 9th) after the re-ranking, they migrated from the “A” group to the “D” group. 


## Implications on of emoving the ninth-grade Math and Reading Scores by:  

### Math & Reading Grade
The removal of the Thomas 9th graders has an obvious effect on the outcome of the math and reading scores for the 9th grade tables specifically. Since all of the Thomas 9th graders received Nan scores for the time being, their math and reading average are effectively Nan as well, so they are unranked within the 9th grade classes at the fifteen schools. Since the academic investigation is limited to just the one class at Thomas HS, there is no change in the 10th, 11th and 12th grade classes and their respective scores and ranking. 

### School Spending
In the table of spending per student the general theme was that spending per capita does not necessarily correlate to higher performance. Lower per capita spending schools tended to outperform higher spending schools in all passing percentage categories. 
Thomas HS spends, on average $638/student annually which puts them in the second highest spending bucket ($630-644/) of schools. When the Thomas 9th graders are excluded from the segmented table, passing rates for math, reading and overall drop about 7% in each category (Math: 73.5% to 66.9%; Reading: 84.4% to 77.5%; Overall: 78.9% to 72.2%). What makes this somewhat peculiar is that it widens the gap for all passing rates for the $630-644 bucket relative to the next lower spending bucket ($585-629) which expected, but it also brings the $630-644 bucket lower than the highest spending bucket ($645-675) which bucks the expected trend that higher spending per capita schools perform worse. One potential explanation is the effect of removing the Thomas 9th graders from the group has a substantial impact on the final results. 

### School Size
Thomas HS is a medium size school so the small and large schools results are unaffected by the Thomas 9th grades situation. However, the re-classification of the Thomas 9th graders scores does affect the passing percentages for math, reading and overall in the Medium size schools. 
For Medium-sized schools, the Math Passing Percentage went from 93.6% to  88.3%, the Reading Passing Percentage dropped from 96.8% to 91.3% and Overall Passing Percentage dropped from 95.2% to 89.8%. 
While it is not unexpected that percentages would drop since a large block of students are not being considered as potentially passing students, the new passing percentages does provide some consistency that was lacking in the original table. In the original table the passing percentages for small and medium schools were nearly identical while large schools were markedly different (25% less for math, 14% less for reading and 19% less for overall passing percentage).
With the new results discounting the Thomas 9th graders, the medium size school passing percentages have results that are closer to a split between the small and large schools. 

### School Type
Thomas HS is a charter school so the exclusion of the Thomas 9th graders adversely affects the Charter school passing percentages. Math Passing rates drop from 93.6% to 90.3%, Reading Passing rates drop from 96.6% to 93.1% and Overall Passing rates drop from 95.1% to 91.7%. 
This drop, while unfortunate, likely won’t change perceptions of charter school reputations as the resulting passing percentages are still considerably higher than district schools. 

## Other Considerations:
The pending status of the grades for the 9th graders at Thomas HS is certainly disappointing but it has highlighted as a potential reason why certain segmented analyses appeared peculiar. However, it would be unfair and reckless to assume that every single 9th grader at the school was party to the academic improprieties. 
