# pandas-challenge

Introduction: 
The Pandas software is mainly used in dataframes, which is meant for data analysis. Pandas has much simpler instructions when coding, and can manipulate data by using operations such as merging , reshaping, and inserting data, as well as data cleaning. This week's challenge assesses these skills and many more when determining specific data regarding high performing and low performing schools, and summaries over the district.  

Overview of the Data:
Through an extensive series of coding operations, we were able to determine a district summary, which includes information such as the total amount of school and students in the district, total budget, and specific data about math and reading scores throughout the whole district. After looking at the big picture, we dug a little deeper to determine that same information for each of the fifteen listed schools. From there, the top 5 best performing and bottom 5 worst performing schools were listed, with the same data that was derived from the previous task. The main difference between these tasks is the fact that the data explicitly shows which school was considered "best performing", "worst performing", or simply in the middle. The average of math and reading scores between the grades of 9th-12th were filtered out, and later used towards the section where the average spending ranges per student was determined.

While most data was cleaned out at this point, we were asked to still determine the scores based on school size, where the commands were typed out since the dataframes were created from previous tasks. Lastly, the scores were compared based on school types (whether the school was a charter school or from the district). This can be valuable information to not only the principals of each school, but to the superintendent of the district. 

Data Limitations:
Some of the data limitations for this challenge was the fact that we were only limited to seeing one district. Although it is important to see how each high school in the district is doing, I believe a lot can be learned from using the same skills onto different district reports. This can help determine what each school is doing right (or wrong), and fix that so that eventually they could all have similar data. 

Another limitation from this challenge was that it was only for high schools. The data could be divided between elementary, middle, and high schools to see how the district, as a whole, is performing. It would not be ideal to compare elementary school data and high school data, but it would be helpful as a superintendent to keep watch of every school in that district.

Methods
For the first section of the experiment, basic functions were used. These include ".sum()", ".mean()", and even dividing the whole from the part to determine percentages. Along with the simple functions, dictionaries were created to eventually create a different dataframe with the information that was asked using ".DataFrame()". Similarly, the second section asked for the same information, however, it was specifically for each school. Whereas the first activity asked about data as a district, the second section was meant to see how each school is doing individually.

Using the information, and even dataframes mentioned from above, we were able to determine the top 5 best-performance schools and bottom-5 worst performing schools. Specifically ".sort_values()" and ".head(5)" were used for the information to be pulled. For the top-performing schools, the ascending had to be noted as False in order to give us the information in a descending manner, and the opposite was done for the bottom 5 worst performing school.

Next, the math and reading scores by grade were determined by grouping each series of each school, combining all of the 9th, 10th, 11th, and 12th graders of the district. The average for each of them was determined using ".mean()", and a dictionary was created afterwards to push the information into one dataset, later used through the function "pd.DataFrame()". It was later determined that Holden High school held the highest average for 9th-11th graders in math scores. For reading scores, most of the schools were roughly the same. 

Conclusions:
In conclusion, Pandas is highly effective when importing large data records, such as district information about each school. This was a perfect example to work on the skills that were taught due to the file having an excessive amount of data. Skills such as merging, grouping, creating bins and dictionaries, and even simple functions like finding out the sum or average of a column were used to accomplish the goal. 
