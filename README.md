# School_District_Analysis
Analyzing a collection of school district data
# PyCitySchools Challenge Analysis

**1. How is the district summary
affected?**
  With the amount of data in this summary, scores are affected on a much smaller scale. With the higher, fraudulent scores removed, however, we do see a slight drop in "Average Math Scores" (-.1%), "% Passing Math" (-1%), "% Passing Reading" (-1%), "& Overall Passing" (-1%).
  
**2. How is the school summary
affected?**
  Similarly to the effects seen on the overall district summary, both Reading and Math scores dropped -- further highlighting the fact that the fraudulent, removed scores were on the higher end. Where we see the largest movement is in the "% Passed" for both Reading and Math. With the "NaN" not qualifying as a passing grade, we saw an approximately 26% and 28% drop in % Passed for Math and Reading respectively. 
  
**3. How does removing the ninth
graders’ math and reading scores
affect Thomas High School’s
performance, relative to the other
schools?**
  After the fraudulent scores are removed from Thomas High School, the school's performance fell from the **2nd** highest performing school (based on "% Overall Passing") to the **8th** highest performing school (out of 15).
  
**4. How does removing the ninth
grade scores affect the following:**

  **- Math and Reading Scores by Grade**
    With the fraudulent scores removed, the district-wide Math scores for the 9th grade fell from 80.4% to 80.1% while the Reading scores for the same group fell similarly from 82.5% to 82.4%
    
  **- Scores by School Spending**
    With a per student spending rate of $638.00, Thomas High School falls into the $630-$644 range we used to break up our 15 schools. With the fraudluent grades removed, the overall passing rate for those schools fell 7% (from 63% to 56%).
    
  **- Scores by School Size**
    With a student population of 1635 Thomas High School falls into the "Medium (1000 to 2000)" category. After these scores were removed, the "% Passing Math" rate fell from 94% to 88% and the "% Passing Reading" rate fell from 97% to 91%, bringing down the overall passing rate 6% (from 91% to 85%).
  
  **- Scores by School Type**
    Thomas High School, being a Charter School, dropped the "% Passing Math" and	"% Passing Reading" scores by 4% for both categories. 
