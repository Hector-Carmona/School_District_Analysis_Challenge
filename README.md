# School_District_Analysis_Challenge
Module 4 Challenge

## Overview of the school district analysis

### Background

>The school board has notified Maria and her supervisor that the analysis is compromised since the file used for the analysis shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders.

### Purpose

Carry the school district analysis out without the compromised data and describe how these changes affected the overall analysis.

## Results

- How is the district summary affected?

### Original vs Modified 

|           | District Summary Including Ninth graders  | District Summary without Ninth graders  |
| :------------ |:---------------:| :-----:|
| Output        | ![Distric Summary 1](https://user-images.githubusercontent.com/86028032/126103315-b675d78d-f3c5-40de-9c67-58d580688133.PNG) | ![Distric Summary 2](https://user-images.githubusercontent.com/86028032/126103346-02ca9ad1-e36a-4bef-b64c-9a6cfd4cd494.PNG)
 
- The district summary is affected in the % passing math, % passing reading,and the % overall passing data that we retrieve, since we are performing the analysis considering 38,709 student for the Thomas High School


- How is the school summary affected?
### Original vs Modified 

|           | School Summary Including Ninth graders  | School Summary without Ninth graders  |
| :------------ |:---------------:| :-----:|
| Output        |![School Summary 1](https://user-images.githubusercontent.com/86028032/126104230-466ea491-4c11-4af3-ab33-0c32748d2c7a.PNG) | ![School Summary 2](https://user-images.githubusercontent.com/86028032/126104244-f675c031-07d6-4151-8dad-8373f37b2875.PNG)


- The school summary is affected in the % passing math, % passing reading,and the % overall passing data that we retrieve, since we are performing the analysis considering 38,709 student for the Thomas High School. Getting lower values and 30% less persons passing both math and reading.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* Since we are considering less data, it affects in positive way the performance of Thoomas High School's. putting it within the 5 top schools.
![performance](https://user-images.githubusercontent.com/86028032/126104863-5d55e585-3c94-42f6-890e-a5dec6adf020.PNG)

How does replacing the ninth-grade scores affect the following:
 * Math and reading scores by grade
   * For "Thomas High School" there's no data, since it was replaced with non values, as seen in the next figure
![Math and reading scores by grade](https://user-images.githubusercontent.com/86028032/126105372-cb08be71-481c-4a8b-aba9-6cd42ccbdfaf.PNG)


  * Scores by school spending

![spending summary](https://user-images.githubusercontent.com/86028032/126106427-6dba5857-519a-4179-9cdb-e975e6b32997.PNG)


  * Scores by school size
    * For the school size analysis, "Thomas High School remains within the medium size cassification
![School Size](https://user-images.githubusercontent.com/86028032/126105992-df178f8d-d142-40ba-bbdf-695ce96502fd.PNG)


  * Scores by school type
 
 ![school type](https://user-images.githubusercontent.com/86028032/126106295-7cd4fe93-3d16-4515-98bb-03b2435e0470.PNG)

 
## Summary

- Four changes to the school district analysis after reading and math scores have been replaced:
  * Thomas High School got new total student count, in other words, we have less students for this specific school for the analysis.
  * The passing reading, math, and overall percentage was affected
  * Since we have less data Thomas High School got whithin the top 5 schools, 
  * Thomas High School cannot be included for the grader level 9th analysis, since we are considering that the data was modified 
