# Final Project - Race Performance
---

### Purpose
This was the capstone project for my UC Davis Data Analytics course designed to practice full stack data visualization development with machine learning. It includes the following:
- SciKit Learn machine learning
- Python, NumPy, Pandas, and Jupyter to clean and organize data
- Tableau Public vizualizations, dashboards, and stories
- Interative Plotly charts (images)
- A JavaScript library not covered in class (Granim - watch the image on the home screen change colors)
- Two datasets (577,000 rows and 1,900,000 rows each)
- Website utilizing Bootstrap, CSS, and HTML with multiple pages, dropdown menus, and buttons
- Multiple visualizations

This graphic represents the architecture of the project. This is the original architecture that created the Plotly plots in a previous project (see my repository called race_performance_Project-2). I could not host the original architecture on free hosting sites due to the size of my datasets and contract restrictions with my data supplier.  I reorganized my data to not violate the contract and used links to Tableau Public to host my large dataset for free.  I included images of the most interesting Plotly charts created previously.
![Results and Goals](/static/images/architecture.png "System Architecture")

### Lessons Learned
Machine learning was instrumental in determining what to plot to glean insights about my hypothesis (that training and goal setting improves race performance).  I learned I needed to reorganized my data to plot by racer instead of by racer in each race.  Tableau made data visualization quick and easy; however, I found it more straight forward to manipulate my data in Python first.  

### To View
This website can be viewed at [https://drbrenner.github.io/xc_performance_final/](https://drbrenner.github.io/xc_performance_final/ "XC Race Performance Homepage") 


### Original Assignment Intent

+ Use machine learning to determine how much race day variables factors influence race performance improvement (temp, number of racers, gender, etc.) 
+ Find correlations between individual seasonal race improvements and training log information.
+ Get the results in a format coaches and XCStat staff can view interactively without host costs (Tableau, Amazon AWS?).

### Topic

+ This is an interesting topic because many consider training hard as the best way to improve performance. My story will show other factors affecting performance.

+ Factors affecting high school cross country race performance
	-Location (elevation), course (difficulty), heat of location, allergens, goal setting, aggressiveness of goals, home school size, home school location.

### Datasets

+ Two .csv files provided by XC Stats (www.xcstats.com)
	- 577,000 rows of individual race performance statistics since 2011 including a racer id, racer school, racer gender, course id, course distance, previous course time, best course time, if a goal was set/met.
	- 1,900,000 rows of individual training logs including a racer id, date of training, effort value, and feel value.

![Results and Goals](/static/images/dataResultsGoals.png "Results and Goals Data Description")
![Training Logs](/static/images/trainingLogs.png "Training Logs Data Description")

+ Possibly add the following data from outside sources
	- lat/lon of race locations
	- average temperatures (either for cross country season or temperature on race day)
	- allergens in area (average or race day)
	- location of schools (if XC Stats will provide)

### Visualizations

+ Visualizations of factors outside a racer's control
	- bar chart winning race time (y) over years (x) for specific course
	- add male vs female to above chart
	- show school size vs top ten finishes (or school team finishes)
	- show how average temperature (during cross country season) or elevation of home school location (training ground) affects # of top ten finishes

+ Visualizations of factors within a racer's control
	- show how goal setting affects a PR
	- show agressiveness of goal affects a PR
	- show how the porportion of high-effort training days two weeks (consult a coach for predicted ideal time) before a race affects a PR

+ Dashboard inspiration: https://www.datapine.com/blog/wp-content/uploads/2018/05/customer-service-report-team.jpg