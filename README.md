# Module-4-Pandas-Challenge
Analysis (also found at top of code)

To make sure we're looking at all available data, we can create a larger dataframe from both CSV files and then we can begin to analyze. The first dataframe we create is a district summary, which concisely show how many schools and students there are, the total budget for the entire district, averages of all math and reading scores, and percent passing students for both categories as well as an overall.
Then, by completing a school summary, we can further break down the data to show a school's type, student body, budget per student, average scores for both reading and math, as well as percent passing those subjects. With this breakdown, we can show the top performing schools, determined by an overall passing percentage (between math and reading), as well as the lowest performing schools. We can also break down the data by subject (math and reading) to show average scores of all grades (9th to 12th).
Our final analyses depicts the type of school, the ranges of how much each school spends on its students, the ranges of the student body size, and each range's average scores for both reading and math, as well as percentages for those students passing the subjects.

With these analyses and charts drawn, one of the conclusions we can draw is that the top five performing schools (performance consisting of percentage of students who pass both reading and math) are charter schools, which typically have a smaller total number of students. This might lead someone to conclude that there might be less stress on educators who teach smaller class sizes. On the other hand, we can also see that the five lowest performing schools are district schools, with student bodies almost twice those of charter schools. It seems a highschool student attending a charter school has a higher chance of passing both subjects, even though the per capita amount actually drops along with a school's student count: schools who receive the most amount of money do not always have the highest passing rates. Another conclusion we might draw is the performance of all students (9th to 12th grade) on reading compared to math. Average reading scores across all schools and grades are consistently in the 80s, whereas math scores somewhat drop.

Acknowledgments:
I received some pushes in the right direction from classmates Sneha Thomas and Ethan Musa (again, thank you so much!) as well as Taylor Ward. I also used various pages on the geeksforgeeks.com and pandas.pydata.org websites, especially the pages on pd.cut, pd.concat, and pd.merge.
https://www.geeksforgeeks.org/pandas-cut-method-in-python/
https://www.geeksforgeeks.org/pandas-concat-function-in-python/
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html
