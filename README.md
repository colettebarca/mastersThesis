# relatedProjects
View the codes and written reports for some of my most involved projects. A brief overview of each project's goals and outcomes is given below.

## Master’s Thesis: Detecting Potential College Dropouts Among High School Students
### Goal: 
Use anomaly detection techniques to create a holistic early detection tool that indicates which high school students are most at risk to drop out of college. An individual’s high school experience is not confined to the academic components. As such, an effective model should incorporate both environmental and educational factors, including various descriptive data on the student’s home area, the school’s area, and the school’s overall structure and performance. This project combined this information with data on students throughout their secondary educational careers (i.e., from ninth through twelfth grade) in an attempt to develop a model that could detect during high school which students have a higher probability of dropping out of college.

### Outcome:
The clustering-based and classification-based anomaly detection algorithms detail the situational and numeric circumstances, respectively, that most frequently result in a student dropping out of college. High school administrators could implement these models at the culmination of each school year to identify which students are most at risk for dropping out in college. Then, administrators could provide additional support to those students during the following school year to decrease that risk. College administrators could also follow this same process to minimize dropout rates.<br><br>

## Predicting College Football Recruits Using Machine Learning Techniques
### Goal: 
Build a supervised learning model to predict whether a high school recruit will commit to a school in one of the Power Five Conferences. Such a model could allow a school to optimize its recruiting process, maximizing its return on investment. This project trained on a dataset with 15 predictors (5 categorical and 10 continuous), consisting of an unprecedented combination of player-specific physical, performance, and geographical attributes.

### Outcome:
The Random Forest model produced the best results when applied to the testing set, as it splits observations using only the most influential predictor from a subset of the predictors for each internal node and decorrelates its produced trees. The final model produced the lowest MSE and highest model accuracy percentage of 0.1109 and 84.90%, respectively. This model revealed which particular attributes are indisputably the most statistically significant predictors of commitment to a Power Five school. <br><br>

## Predicting a Film’s Success Before Filming Begins
### Goal: 
Create a statistical model for prospective financiers that would predict if a movie would be successful based on its proposed featured actors, director, producer, writer, genre, and production company. In this context, a film’s success is quantified using its percent return on investment (ROI).

### Outcome:
The zero percent ROI’s Logistic Regression model fit with only the four statistically significant predictors produced the most accurate predictions. This suggests that, using the information typically presented with film packaging, it is possible to predict if a particular film will lose money. However, such information is not as effective for predicting how successful the project will be.<br><br>

## Airline Reservation System
### Goal: 
Create a seat reservation system for an airline. Plan flight schedules between airports based on the data file to accommodate maximum passengers, maintaining a high average seat occupancy rate per day.

### Outcome:
Created a reservation system that accomplishes the following:
1. Identifies passengers by a passenger ID that can be retrieved with all personal information given in the data file.
2. Make seat arrangements defined by three classes (economy, business, and first class).
3. Identifies airports by IATA codes.
4. Creates and books flights by departure time, origin airport, and destination airport.
5. Reserves seats for each passenger on a first come first served basis. These reservations allow automatic upgrades to the next available upper-level class or downgrades to the next available lower-level class if the requested class is full to accommodate all co-passengers.
6. Reports the number of available seats in each class on a given flight.
7. Indicates whether the passenger checked-in for the flight within the 24-hours prior to take-off. 
