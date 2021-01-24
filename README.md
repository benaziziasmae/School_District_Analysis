# School_District_Analysis

School District Analysis using Anaconda, Jupyter Notebook, Pandas & Python.

You can find the code [here.](/PyCitySchools_Challenge.ipynb)

## Overview of the school district analysis

 1- Data

 In this project we were given access to both [school_complete](/Resources/schools_complete.csv) and [student_complete](/Resources/students_complete.csv) data to perform an analysis regarding every student's math and reading scores, as well as various information on the schools they attend. And help to make a strategic decision regarding the future shcool budget and priorities.
 
 2- Purpose of the project
 
The purpose of the project is analyse the following data of the High Schools before and after a possible academic dishonesty, where the data for 9th Grade of Thomas High School has been upheld for the analysis purpose. We have replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will analyse the data before and after making this change.

First, our responsability is to aggregate data and showcase obvious trends in school performance. Our final report should include each of the following (deliverable 2):

 - The district summary.
 - The school summary.
 - The top 5 and bottom 5 performing schools, based on the overall passing rate.
 - The average math score for each grade level from each school.
 - The average reading score for each grade level from each school.
 - The scores by school spending per student, by school size, and by school type.
 
## Results

 1- Deliverable 1:
 
 In the deliverable 1, we were assigned to select the ninth-grade reading and math scores for Thomas High School, by using the Pandas NumPy module to change the reading and math scores to NaN, which represents a "Not-a-Number" value, using the Pandas loc method with conditional statements and comparison and logical operators.
  
  After running the code we had the following results.
  
  
  ![delivereable_1_NaN](/Resources/deliverable_1_NaN.PNG)
  
  
   1- Deliverable 2:
   
In the deliverable 2, we were assigned to repeat the school district analysis already done in this module, and to recreate the following metrics:
    
  1-1 The district summary.
  
  1-2 The school summary.
  
  1-3 The top 5 and bottom 5 performing schools, based on the overall passing rate.
  
  1-4 The average math score for each grade level from each school.
  
  1-5 The average reading score for each grade level from each school.
  
  1-6 The scores by school spending per student, by school size, and by school type.
   
   *1-1 The district summary*
   
   ![after_district_summary](/Resources/after_district_summary.PNG)
   
   
 It gives the district's key metrics, including:

- Total Schools
- Total Students 
- Total Budget 
- Average Math Score  
- Average Reading Score
- % Passing Math (The percentage of students that passed math.) 
- % Passing Reading (The percentage of students that passed reading.)
- % Overall Passing (The percentage of students that passed math and reading.)

And since some of the test scores from the 9th grade at Thomas High School are missing we want to take all of the scores from the high school so that it doesn't affect our overall numbers.
   
   *1-2 The school summary*
   
   ![after_school_summary](/Resources/after_school_summary.PNG)
   
   
 It creates an overview table that summarizes key metrics about each school, including:

- School Name 
- School Type 
- Total Students 
- Total School Budget
- Per Student Budget 
- Average Math Score 
- Average Reading Score 
- % Passing Math (The percentage of students that passed math.) 
- % Passing Reading (The percentage of students that passed reading.) 
- % Overall Passing (The percentage of students that passed math and reading.)


    *1-3 The top 5 and bottom 5 performing schools, based on the overall passing rate*
    
     ![top_and_bottom_schools](Resources/after_top_and_bottom_schools_.PNG)
     
   
    *1-4 The average math score for each grade level from each school*

   ![after_average_math_score](Resources/after_average_math_score.PNG)
   
 
 
  *1-5 The average reading score for each grade level from each school*
  
   ![after_average_reading_score](Resources/after_average_reading_score.PNG)
   
   
   *1-6 The scores by school spending per student, by school size, and by school type*
   
     a- By school spending per student
   
   ![school_spending_summary](Resources/after_school_spending_summary.PNG)
   
   
    b- By school size
    
    ![school_size_summary](Resources/after_school_size_summary.PNG)
    
     c- By school type
     
     ![school_type_summary](Resources/after_school_type_summary.PNG)
    
   ## Analysis and challenges
   
 **1- How is the district summary affected?**
   
   If we compare the results from PyCitySchools and PyCitySchools_Challenge, we can see a slight difference in the results: 1% drop avg math score and reading between two analysis:
   
   - Average math and reading scores dropped just by 1%, i.e. from 79.9% to 79.8% and 81.8% to 81.9% respectively.
   - % Passing Math, % Passing Reading and % Overall passing also showed 1% drop after the change from 74.9% to 74,8%, from 85.8% to 85.7% and 65.1% to 64.9% respectively.
   
   *District Summary after*
    
![after_district_summary](/Resources/after_district_summary.PNG)

*District Summary before*

![before_district_summary](/Resources/before_district_summary.PNG)
    
       
 **2- How is the school summary affected?**

-  The data remains unaffected for all schools except for Thomas High School which showed a drasctic drop passing %. 
- % Passing Students for Math and Reading for Thomas High School came considerable down from 93.27% to 66.91% and 97.31% to 69.66% respectively.
- % Overall passing students for Thomas High School came down from 90.95% to 65.08%.

*School Summary after* 

 ![after_school_summary](/Resources/after_school_summary.PNG)
 
 *School Summary before* 
 
 ![beforer_school_summary](/Resources/before_school_summary.PNG)



  **3- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Thomas High School's performance decreased compared to the other schools however, it is not one of the lowest performing schools.
Thomas High School for both after and before doing the chages remain among the top ranked schools.
Howerver, the avverage Math Score and Average Reading scores dropped a bit, which impacted the % overall Passing which dropped from 90.94% to 90.63%.
 
 *After top and bottom summary*
 
 
 ![after_top_and_bottom_schools_](/Resources/after_top_and_bottom_schools_.PNG)
 
* Before top and bottom summary*
 
![before_top_and_bottom_schools_1](/Resources/before_top_and_bottom_schools_1.PNG)

  **4- How does replacing the ninth-grade scores affect the following:** 
 
  -- Math and reading scores by grade

- The 9th grade scores were brought down as Thomas High School 9th graders averaged higher than other schools.
- The average math and reading scores of Thomas High School became 0 from 83.6 and 83.7 respectively.


*After Math scores by grade*

![after_average_math_score](/Resources/after_average_math_score.PNG)

*Before Math scores by grade*

![before_average_math_score](/Resources/before_average_math_score.PNG)


*After reading scores by grade*

![after_average_reading_score](/Resources/after_average_reading_score.PNG)

*Before reading scores by grade*

![before_average_reading_score](/Resources/before_average_reading_score.PNG)

  -- Scores by school spending

The numbers stay nearly identical since the 9th graders are nullified from the statistics.
In the cohort $630-644, % passing math, % passing reading and % overall passing have not changed after changing the grades to NaN.


*After school spending*

![after_school_spending_summary](/Resources/after_school_spending_summary.PNG)

*Before school spending*

![before_school_spending_summary](/Resources/before_school_spending_summary.PNG)


  -- Scores by school size

The average math and reading score, the % passing math and reading and the % Overall students passing remained unaffected, with all the school size types variying from small(<1000) to large(2000-5000)especially that Thomas High School fell in the Medium Category(1000-2000).


*After school size*

![after_school_size_summary](/Resources/after_school_size_summary.PNG)

*Before school size*

![before_school_size_summary](/Resources/before_school_size_summary.PNG)


  -- Scores by school type

The score by school type was not affected by the change in the 9th grade, all the indicators remain the same.

*After school type*

![after_school_type_summary](/Resources/after_school_type_summary.PNG)

*Before school type*

![before_school_type_summary](/Resources/before_school_type_summary.PNG)

# Conclusion

  The four major changes that occured between the two analyses were:

 - Without the 9th graders' scores, Thomas High School is not as competitive with other charter schools.
 - The average math and reading scores were dropped slightly at district level.
 - The percentage passing students for math, reading and overall was also significantly affected at school and grade level for Thomas High School after the change.
- All academic parameters related to math, reading and overall score were remain the same which ever category of type, size and school spending per student Thomas high School fell into.
 
   
