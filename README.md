# School_District_Analysis
## Overview of PyCitySchool Challenge

We are working with City School District's Chief Data Scientist, Maria. Maria has asked that we help analyze the district data for standardized test scores and student funding. After preparing and presenting the findings to the schoolboard, Maria was notified of some possible academic dishonesty at Thomas High School 'THS'. We have been asked to replace the 9th grade scores at THS with NaN and update all the district numbers with this change.

##Deliverable 1
  The first step was to replace all 9th grade scores at Thomas High School with NaN as seen below:
  ![Deliverable 1](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/deliverable_1.png)
  
##Deliverable 2
  Deliverable two is reanalyzing all of the district data after the 9th grade Thomas High School information has been removed. The first three steps are shown below
  ![Deliverable_2](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/deliverable_2.png)
###Analysis

#### How is the district summary affected?
  Replacing the 9th grade students at just one school has very little overall effect on the district. Below is a comparison of before and after the data was cleaned up.
  
#### What Changes were found?

* The original summary for the district shows an average math score of 79 with a passing percentage of 75% and average reading score of 81.9 with a passing percentage of 86%. Overall, the original district has a passing rate of 65%
![original_district_summary](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/original_district_summary.png)
* After removing THS 9th graders the school district numbers are now very similar. Average math score has dropped to 78.9 with a passing percentage of 74.8%. Reading scores did not change, but the percentage went down to 85.7%. Overall, the district passing percentage changed to 64.9%
![new_district_summary](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/new_district_summary.png)

* Thomas High School saw a significant change with the overall passing percentage once the 9th grade information was removed. The percentage went from 97.3% down to 90.63%

* For the top and bottom 5 schools, there was no affect with removing the 9th grade scores. Thomas High School is still ranked second.
![original_top_bottom_schools](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/original_top_bottom_schools.png)

and the new rankings:
![new_top_bottom_schools](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/new_top_bottom_schools.png)

* While the 9th grade data affects Thomas High School, it does not affect any other grade level nor does it affect other schools.
Original Math Grades
![original_math_grades](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/original_math_grades.png)
And the new grades when 9th graders at THS are replaced with NaN
![New_math_grades](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/new_math_grades.png)


* The same was shown with the average reading scores. Here is the new calculation:
![New_reading_scores](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/new_reading_scores.png)

* There was no difference between spending per student, by size, and by type when calculated with or without the Thomas High School 9th grade scores. For example, below is the original and new calculations by size of school.
![original_size_school](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/original_size_school.png)
and new calculations:
![new_size_school](https://github.com/stacybeauregard/School_District_Analysis/blob/main/Resources/new_size_school.png)

###Summary
While there was very little affect with removing scores and replacing with NaN, Thomas High School was affected on an individual level.
* Thomas High Schools overall passing grade dropped due to no data being available from the 9th grade students.
* The District overall passing percentage was slightly reduced to just below 65%
