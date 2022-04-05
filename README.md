# RoadSafety
This project attempts to classify the severity of injury (None, Minimal/Minor, Major, or Fatal) using data from all traffic 
collisions events where a person was either Killed or Seriously Injured (KSI) from 2006 – 2020. RandomForest Classification was 
chosen for the model. 

The Dataset was last updated on May 1, 2021 
Dataset can be downloaded from the Toronto Police Services Website for Total Killed or Seriously Injured (KSI) Collisions 
https://data.torontopolice.on.ca/datasets/TorontoPS::ksi/about

The dataset includes 54 features and 16,860 records

Name	         Description<br>
INDEX         Unique Identifier
ACCNUM        Accident Number
YEAR          Year Collision Occurred
DATE          Date Collision Occurred
TIME          Time Collision Occurred
HOUR          Hour Collision Occurred
STREET1       Street Collision Occurred
STREET2       Street Collision Occurred
OFFSET        Distance and direction of the Collision
ROAD_CLASS    Road Classification
DISTRICT      City District
WARDNUM       Ward Number
DIVISION      Division Number
LATITUDE      Latitude
LONGITUDE     Longitude
LOCCOORD      Location Coordinate
ACCLOC        Collision Location
TRAFFCTL      Traffic Control Type
VISIBILITY    Environment Condition
LIGHT         Light Condition
RDSFCOND      Road Surface Condition
ACCLASS       Classification of Accident
IMPACTYPE     Initial Impact Type
INVTYPE       Involvement Type
INVAGE        Age of Involved Party
INJURY        Severity of Injury
FATAL_NO      Sequential Number
INITDIR       Initial Direction of Travel
VEHTYPE       Type of Vehicle
MANOEUVER     Vehicle Manouever
DRIVACT       Apparent Driver Action
DRIVCOND      Driver Condition
PEDTYPE       Pedestrian Crash Type - detail
PEDACT        Pedestrian Action
PEDCOND       Condition of Pedestrian
CYCLISTYPE    Cyclist Crash Type - detail
CYCACT        Cyclist Action
CYCCOND       Cyclist Condition
PEDESTRIAN    Pedestrian Involved In Collision
CYCLIST       Cyclists Involved in Collision
AUTOMOBILE    Driver Involved in Collision
MOTORCYCLE    Motorcyclist Involved in Collision
TRUCK         Truck Driver Involved in Collision
TRSN_CITY_VEH Transit or City Vehicle Involved in Collision
EMERG_VEH     Emergency Vehicle Involved in Collision
PASSENGER     Passenger Involved in Collision
SPEEDING      Speeding Related Collision      
AG_DRIV       Aggressive and Distracted Driving Collision
REDLIGHT      Red Light Related Collision
ALCOHOL       Alcohol Related Collision
DISABILITY    Medical or Physical Disability Related Collision  
POLICE DIVISION Police Division
HOOD_ID       Neighbourhood Identifier  
NEIGHBOURHOOD Neighbourhood Name  
FID           Object ID (Unique Identifier)
X             Latitude
Y             Longitude
