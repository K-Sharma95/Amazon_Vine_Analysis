# Amazon_Vine_Analysis


Module 16

## Overview 
The purpose of this project is so analyze school data; such as test scores, student numbers, passing paramteres etc., in order to provide more detailed information
about these schools and these students. These analyses are completed through Python and Jupyter Notebook software(s), using skills such as building Dataframes, 
changing or manipulating data, and seeing how these changes affect the bigger picture. 

## Results
Upon finding evidence of academic dishonesty in the test scores of Thomas High School ninth graders, both the math and reading score are compromised.This can be observed in the
[Resources/students_complete.csv](Resources/students_complete.csv).Our client Maria has tasked us with removing these score, replacing them with a "NaN' value, and then re-analyzing the data from there. Unfortunately I was unable to complete the removal of these scores, however I have completed all other requirements. Therefore my results will be
also based on a best educated guess, and I will try my best to accurately predict these results. 
After replacing the fraudulent grades with "nan", we can estimate the following:

* **How is the district summary affected?**

Thomas Highschool averages and the associated district averages will go down.

* **How is the school summary affected?**

The overall passing rate in Thomas High School will go down


* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Unfortunately given my incomplete code, the position relative to other schools post removal is incomplete. I do predict however that the school will ranksubstantially lower, due to the removal of a large number of high-performing students. 

* **How does replacing the ninth-grade scores affect the following:**
* **Math and reading scores by grade**

All grades except the ninth grade are affected minimally. Ninth grade scores are largely Nan post removal. 

* **Scores by school spending**

The score goes down, therefore Thomas High School ranks lower per dollar spent post grade removal. 

* **Scores by school size**

The scores based on school size will decrease. Thomas High school is in the "medium" school bucket. 

* **Scores by school type**

Due to my lack of information I am unable to comment on this section. 

## Summary 
In summary based on my incomplete data and assignment I can list four major changed I EXPECT to occur once the fraudulent scores have been replaced with "NaN'
Firstly, Thomas High School will receive a lower rank and many metrics/averages will also be lowered. Secondly the spending ranged will increase per student at 
Thomas High School. Thirdly the statistics for the Charter school will also decrese in relation to less students passing math and reading. Fianlly I can observe that 
the school_district_analysis will provide a more realistic overview of the school and associated students post grade removal. 
