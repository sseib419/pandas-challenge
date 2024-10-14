# pandas-challenge

In order to complete this analysis, two data sets were loaded into Jupyter notebook that contained school and student data. Those sets were merged together and after calculating key metrics, a data frame was created that gave a high-level snapshot of the district. 

In order to get a summary of the key metrics for each school, a few columns from the school data were pulled and the index was set to be the name of the school. The average math score (78.99) and average reading score (81.88) for all the students in the district were calculated. Then using the group by function, the average math and reading score was calculated for each school, and the percentage of students with math scores greater or equal to 70, reading scores greater or equal to 70, and the number of students who had both reading and math scores greater or equal to 70 were found. These calculations were placed into a dataframe. 

The highest and lowest performing schools were shown using the sort function on the "% overall passing" column. 

Math and reading scores were filtered by each grade using .loc, the group by function was used to calculate the average of the scores, and data frames showing the math and reading averages for each grade was created.

The spending ranges per student was found by creating bins for each range of spend and cutting on the "per student budget" column from a previously created data frame, then the group by was used to get the average scores and percentages for each spending range, and a data frame was created. The same binning procedure was done to get the average scores and percentages for each school size range. Lastly, a data frame containing the averages of the scores and percentages by school type was created using the group by function. 

A conclusion drawn from these calculations is that in general, students who attend charter schools have higher scores in math & reading compared to students in district schools. Another conclusion drawn is that the more students a school has, the lower the math and reading scores are, with large schools having a much lower overall passing percentage compared to small schools. This could be due to having less resources to spread around with schools that have a larger student population, as well as less attention given to each student, although we do not know the teacher to student ratio for each school size which could be something that is found in a future analysis. 
