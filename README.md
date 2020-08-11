# School District Analysis

## Overview of Project
The goal of this project was to merge data from two difference excel sheets and reviewed statistics about the schools and students according to this data. Later on we received word that some of the data had been compromised. We adjusted our statistics accordingly and will review the changes below.

### Results of School & Student Analysis
1. You can see in the district summary that we had a slight decrease in all our averages and passing grades.
	- Original Results:
![district_summary_before](https://raw.githubusercontent.com/si1ver1/school_district_analysis/master/analysis/disctrict_summary_before.jpg)  
	- Cleaned Results:
![district_summary_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/disctrict_summary%20after.jpg)

2. We can see in the school summary, even though the average scores only go down a little the passing % goes down drastically.
	- Original Results:
![school_summary_before](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/school_summary_before.jpg)
	- Cleaned Results:
![school_summary_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/school_summary_after.jpg)

3. If we look at the school relative to others, we can see that Thomas High School lost its status of second highest passing school. It ends up in 8th place out of 15 schools.
	- Original Results (top 5):
![top_schools_before](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/top_schools_before.jpg)
	- Cleaned Results (top 5):
![top_schools_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/top_schools_after.jpg)

4. Replacing the scores had these effects listed below.
    -   Math and reading scores by grade: are not really changed other than all 9th grade scores will display as nan in the new data:
![nan_scores](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/nan_scores.jpg =300x)
    -   Scores by school spending went down for all % passing under the $630-644 range.
		- Original Results:	![scores_by_spending_before](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_by_spending_before.jpg)
	    - Cleaned Results:![scores_by_spending_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_by_spending_after.jpg)
    -   Scores by school size: The passing scores all went down for the medium sized schools (the range that Thomas High School was part of).
	    - Original Results:
![scores_schoolsize_before](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_schoolsize_before.jpg)
	    - Cleaned Results:
![scores_schoolsize_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_schoolsize_after.jpg)
    -   Scores by school type: Thomas High School was a Charter school so we notice that passing scores went down for Charter schools.
	    - Original Results:
![scores_schooltype_before](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_schooltype_before.jpg)
	    - Cleaned Results:
![scores_schooltype_after](https://raw.githubusercontent.com/si1ver1/School_District_Analysis/master/analysis/scores_schooltype_after.jpg)

### Summary
The four biggest changes:
1. School ranking by % overall passing went down a lot. The school was previously a top 2 passing school but went down to number 8 out of 15.
2. The % passed for math, reading and both previously went up as spending increased but now some of those values are no longe linear.
3. The % passed for math, reading and both for just Thomas High School went down drastically.
4. The changes mentioned in #3 also caused the overall summaries by school type and district to go down slightly.
