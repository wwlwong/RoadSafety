# SCS3252 Machine Learning Team Project
# RoadSafety

Team members:<br>
Nafe McNafee<br>
Ketan Khanna<br>
William Wong<br>

Problem:<br>
In the past 10 years, the number of fatilities caused by traffic collision ranges between 34 - 78 per year. 

This project attempts to classify the severity of injury (None, Minimal/Minor, Major, or Fatal) using data from all traffic 
collisions events where a person was either Killed or Seriously Injured (KSI) from 2006 – 2020. In doing so, patterns from 
road conditions and behaviour could be identified to develop traffic control policies as well as infrastructure design for 
city neighbourhoods.

The Dataset was last updated on May 1, 2021 
Dataset can be downloaded from the Toronto Police Services Website for Total Killed or Seriously Injured (KSI) Collisions 
https://data.torontopolice.on.ca/datasets/TorontoPS::ksi/about

The dataset includes 54 features and 16,860 records

|Name          |Description<br>|
| :------------ |:---------------|
|INDEX         |Unique Identifier<br>|
|ACCNUM        |Accident Number<br>|
|YEAR          |Year Collision Occurred<br>|
|DATE          |Date Collision Occurred<br>|
|TIME          |Time Collision Occurred<br>|
|HOUR          |Hour Collision Occurred<br>|
|STREET1       |Street Collision Occurred<br>|
|STREET2       |Street Collision Occurred<br>|
|OFFSET        |Distance and direction of the Collision<br>|
|ROAD_CLASS    |Road Classification<br>|
|DISTRICT      |City District<br>|
|WARDNUM       |Ward Number<br>|
|DIVISION      |Division Number<br>|
|LATITUDE      |Latitude<br>|
|LONGITUDE     |Longitude<br>|
|LOCCOORD      |Location Coordinate<br>|
|ACCLOC        |Collision Location<br>|
|TRAFFCTL      |Traffic Control Type<br>|
|VISIBILITY    |Environment Condition<br>|
|LIGHT         |Light Condition<br>|
|RDSFCOND      |Road Surface Condition<br>|
|ACCLASS       |Classification of Accident<br>|
|IMPACTYPE     |Initial Impact Type<br>|
|INVTYPE       |Involvement Type<br>|
|INVAGE        |Age of Involved Party<br>|
|INJURY        |Severity of Injury<br>|
|FATAL_NO      |Sequential Number<br>|
|INITDIR       |Initial Direction of Travel<br>|
|VEHTYPE       |Type of Vehicle<br>|
|MANOEUVER     |Vehicle Manouever<br>|
|DRIVACT       |Apparent Driver Action<br>|
|DRIVCOND      |Driver Condition<br>|
|PEDTYPE       |Pedestrian Crash Type - detail<br>|
|PEDACT        |Pedestrian Action<br>|
|PEDCOND       |Condition of Pedestrian<br>|
|CYCLISTYPE    |Cyclist Crash Type - detail<br>|
|CYCACT        |Cyclist Action<br>|
|CYCCOND       |Cyclist Condition<br>|
|PEDESTRIAN    |Pedestrian Involved In Collision<br>|
|CYCLIST       |Cyclists Involved in Collision<br>|
|AUTOMOBILE    |Driver Involved in Collision<br>|
|MOTORCYCLE    |Motorcyclist Involved in Collision<br>|
|TRUCK         |Truck Driver Involved in Collision<br>|
|TRSN_CITY_VEH |Transit or City Vehicle Involved in Collision<br>|
|EMERG_VEH     |Emergency Vehicle Involved in Collision<br>|
|PASSENGER     |Passenger Involved in Collision<br>|
|SPEEDING      |Speeding Related Collision<br>|   
|AG_DRIV       |Aggressive and Distracted Driving Collision<br>|
|REDLIGHT      |Red Light Related Collision<br>|
|ALCOHOL       |Alcohol Related Collision<br>|
|DISABILITY    |Medical or Physical Disability Related Collision<br>|  
|POLICE DIVISION |Police Division<br>|
|HOOD_ID       |Neighbourhood Identifier<br>|  
|NEIGHBOURHOOD |Neighbourhood Name<br>|  
|FID           |Object ID (Unique Identifier)<br>|
|X             |Latitude<br>|
|Y             |Longitude<br>|

Some of the features in the dataset were overlapping (ie. geographical, vehicle involved) and some features were missing significant 
amount of entries thus were dropped. The dataset was split into 70/30 for train/test set.

A series of native multiclass classifiers were evaluated by accuracy score applying the training dataset in a 3 fold cross validation.
The models evaluated included:<br>
Decision Tree<br>
KNN<br>
RandomForest<br>
SVM<br>
SGD<br>
AdaBoost<br>
LogisticRegression(Multinomial)<br>
Naive Bayes<br>
VotingClass<br>

From the evaluation, RandomForest Classification was chosen and the following hyperparameters were tuned.
n_estimators<br> 
max_features<br> 
max_depth<br> 
min_samples_split<br> 
min_samples_leaf<br>
max_leaf_nodes<br>
max_samples<br>




