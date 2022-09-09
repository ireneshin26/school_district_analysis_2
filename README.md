# **School District Analysis**

## **Overview of School District Analysis**
This project was an analysis on school district performance using Jupyter Notebook with Python, Pandas Library, and Numpy Library. 

The school board wanted to understand various performance metrics of the different schools and the district. We were asked to conduct the analysis twice, due to the suspicion that Thomas High School's ninth graders' were altered. In the second analysis, we were asked to replace the math and reading scores for Thomas High School's ninth graders with "NaN"s to see how this change could impact various parts of the performance. 

***

## **Results**

### **How is the district summary affected by replacing Thomas High School's 9th grader data with NaN:**
* Old District Summary
       <img width="1022" alt="Old - District Summary" src="https://user-images.githubusercontent.com/110875578/189269016-afcc0f87-c659-4201-86a9-412eb39c021c.png">

* New District Summary:
      <img width="1032" alt="New - District Summary" src="https://user-images.githubusercontent.com/110875578/189269026-a2639da2-95d1-4647-9ab3-e80d5374c091.png">
      
* Percentage Passing Reading decreased from 86.0% to 85.7%
* Percentage Passing Math decreased from 75.0% to 74.8%
* Percentage Overall Passing decreased from 65% to 64.9%


### **How is Thomas High School's data affectedby replacing Thomas High School's 9th grader data with NaN:**
* Old School Summary
   <img width="1087" alt="Old - School Summary" src="https://user-images.githubusercontent.com/110875578/189269620-80e0f46f-6fbf-4898-8a96-579febffb40f.png">

* New District Summary:
   <img width="1090" alt="New - School Summary" src="https://user-images.githubusercontent.com/110875578/189269298-38e77a5e-72ca-4b4b-93cd-1aad1b9c045e.png">

* Average Math Score decreased from 83.42 to 83.35;
* Average Reading Score increased from 83.85 to 83.90
* Percentage Passing Math decreased from 93.27% to 66.91%
* Percentage Passing Reading decreased from 97.31% to 69.66%
* Percentage Overall Passing decreased from 90.95% to 65.08%
    
### **How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?**
* With the previous analysis, Thomas High School was ranked 2nd but with the new analysis it drops it down in 8th place in terms of percentage overall passing.
   
### **How does replacing the ninth-grade scores affect the following:** 
* **Math and reading scores by grade**: It doesn't have an affect on other school's data nor the 10th-12th grade data for Thomas High School. The only difference is that for the new data, there will be an NaN listed under 9th grade for Thomas High School. 
   * Old Data:
      * Math Scores by Grade by School:<img width="325" alt="Old - Math Scores by Grade by School" src="https://user-images.githubusercontent.com/110875578/189270078-9b133f63-c3f1-4a6c-a75f-00d682eef15e.png">
      * Reading Scores by Grade by School: <img width="327" alt="Old - Reading Scores by Grade by School" src="https://user-images.githubusercontent.com/110875578/189270081-d9de5089-2057-47c4-b2fc-6574a1b616e9.png">
         
   * New Data
      * Math Scores by Grade by School: <img width="322" alt="New - Math Scores by Grade by School" src="https://user-images.githubusercontent.com/110875578/189270190-0125fead-2d5f-4f7f-92c6-0338eacc5963.png">
      * Reading Scores by Grade by School: <img width="331" alt="New - Reading Scores by Grade by School" src="https://user-images.githubusercontent.com/110875578/189270193-720fc93f-4fa1-4224-b826-617ba0d4bc7d.png">

* **Scores by school spending:** There is a very miniscule change shown in the $631-645 spending range. For comparison purposes, snapshots shows more decimals but in the challenge, data points do not have decimal points so data looks mostly the same.
   * Old Data: 
      * <img width="888" alt="Old - Spending Summary" src="https://user-images.githubusercontent.com/110875578/189270811-a9205069-e8b3-4a4a-beb2-91f8235e8829.png">
   * New Data:
      * <img width="900" alt="New - Spending Summary" src="https://user-images.githubusercontent.com/110875578/189270804-f2e4dcd9-e2ef-470d-9662-7b562227679f.png">

* **Scores by school size:** There is a very miniscule change shown in the Medium school size category because Thomas High School falls in that range with 1635 students. For comparison purposes, snapshots shows more decimals but in the challenge, data points do not have decimal points so data looks mostly the same. 
   * Old Data: <img width="833" alt="Old - Scores by School Size" src="https://user-images.githubusercontent.com/110875578/189271104-ae5192fc-b1ac-40db-88bd-8d919c750529.png">

   * New Data:<img width="836" alt="New - Scores by School Size" src="https://user-images.githubusercontent.com/110875578/189271115-e34d2d98-acae-48b2-9895-585fd4fa359b.png">

* **Scores by school type:** There is a very miniscule change shown in the Charter because Thomas High School is a charter school. For comparison purposes, snapshots shows more decimals but in the challenge, data points do not have decimal points so data looks mostly the same. 
   * Old Data: <img width="778" alt="Old - Scores by School Type" src="https://user-images.githubusercontent.com/110875578/189271319-32d83a5e-5a01-4c95-83cd-0f9b7106f2b2.png">

   * New Data:<img width="771" alt="New - Scores by School Type" src="https://user-images.githubusercontent.com/110875578/189271309-189e1325-77a9-4bc3-aa89-ea1ad4d16f20.png">


***
## **Summary**
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Thomas High School dropped from 2nd to 8th out of 15 schools. 
2. Percentage overall passing for Thomas High School dropped from 90.95% to 65.08%.
3. District percentages all went down - reading (86.0% to 85.7%), math(75.0% to 74.8%), overall(65% to 64.9%).
4. When viewing scores by grade data, Thomas High School's 9th grade cell will know NaN

***

## **Links::
Challenge Code: https://github.com/ireneshin26/school_district_analysis_2/blob/main/PyCitySchools%20Challenge.ipynb

***
## **Resources**
Software: Python version 3.9.12
