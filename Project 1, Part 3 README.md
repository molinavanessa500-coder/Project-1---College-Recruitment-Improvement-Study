# Project 1, Part 3: Data Analysis and Visualization
Author: Vanessa Molina

Updated: October 25, 2026

Project Overview:
While using Python, perform an exploratory data analysis of the 2026 CCM Computing Courses Entry Surveys. This is to provide insights that can help the Information Technologies department increase student enrollment in computing classes. I wanted to look mainly into who/what motivated a student into taking a computing class and suggest ways the Information Technologies department can advertise more efficiently to incoming freshmen and current students. 

Questions:
The notebook investigates five questions:
1. How students hear about CCM: Who/What received the highest percentage of “Yes” responses?
2. Impact of school-based computing experiences: What percentage of students reported “Some Impact” or “High Impact” for school-based environments?
3. Motivations for pursuing computing: What are the top 4 reasons students are obtaining a computing degree or certification?
4. Gender identity of survey respondents: Which gender identity had the lowest percentage of enrollment among survey respondents?
5. Interest in additional computing classes: What percentages of non-computing students were not interested, somewhat interested, or interested in taking more computing classes?

Imports - Libraries Used:
 - Python, pandas, Matplotlib, and Jupyter Notebook

Imports - Data Used: 
- The uncleaned version of the Majors Survey Results that was provided to students taking a computing class that is needed for a computing major. 
  - Majors Survey Results - Fall 2026
- Cleaned version of the Major Survey Results. This file has only the columns used to answer the 5 questions:
  - dataclean_major_survey_results_fall_2026.csv

Visualizations: 
To detail the survey findings, I used...
  - Separate horizontal bar charts to see how students heard about CCM and the impact of school-based computing classes/programs influenced their decision to attend computing classes.
  - Separate bar charts to showcase the top 4 motivators for students to get a compuing degree/certification and the gender identity of students who completed the survey
  - A pie chart to show the levels of interest in taking additional computing classes as non-computing major students. 

Results and Conclusions:
Below are some results I wish to highlight found from the survey data:
  - Personal connections are important. Family members or friends were the most frequently selected source for hearing about CCM (63.58%). The CCM website, high school counselors, and high school teachers were also prominent sources (43.93% each).
  - 48.5% of students reported computing classes have either "Some Impact" or "High Impact" in their decision to attend computing classes. High school teachers or counselors were also influential in students' reported experiences just under Computing Classes with 32.4% reporting either some or high impact. 
  - The top motivator for a person to obtain a computing degree/certification is getting a job in the computing field with 96.0%. This is then followed by personal enrichment with 85.0%, and the personal development and career advancement with 81.0% each. 
  - We saw that the majority of responsdents were men, reporting 73.41% identfiy as a man. From this report, 20.81% who completed this survey identify as women, 3.47% as non-binary, and 2.31% prefer not to say. Those that do not identify were 0%.
  - Among non-computing students, 40.58% were interested in taking more computing classes and 35.59% were somewhat interested. 
  - From these results, I suggest that we put more resources towards advertisements and influencers we know impact a student's decision to come to CCM and attend computing classes. An example includes becoming connected to high school teachers and counselors and share with them promotional material and work from current computing students. Another way to increase the number of students working towards obtaining a computing degree/certification or taking computing classes could be advertising towards women, non-binary, those who perfer not to say, or do not identify as a gender. We can utilize the top motivators or bring updated advertisements to middle and high school computer teachers and counselors. Lastly, it is important to understand the interest of non-computing major students. Outreach using the top motivations could help encourage further interest. 


Citations:
  * Binowski, N. E. (2026). “Charts with Matplotlib.” County College of Morris.
  * Deitel, P., and Deitel, H. M. Intro to Python for Computer Science and Data Science. Pearson Education, 2019.
  * McDonald, A. “7 Steps to Help You Make Your Matplotlib Bar Chart Beautiful.” Towards Data Science, March 27, 2023. https://towardsdatascience.com/7-steps-to-help-you-make-your-matplotlib-bar-charts-beautiful-f87419cb14cb/
  * pandas documentation: DataFrame.value_counts. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.value_counts.html
  * “Rotating Axis Labels in Matplotlib.” Python Charts, May 17, 2019. https://www.pythoncharts.com/matplotlib/rotating-axis-labels/
  * “Pie Charts.” Matplotlib Documentation, September 11, 2026. https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_features.html
