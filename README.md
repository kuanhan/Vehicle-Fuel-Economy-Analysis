# Vehicle-Fuel-Economy-Analysis
# Table of contents :
1.  Know Data Attributes
2.  Ask Questions
3.  Data Assessment
4.  Data Preprocessing and Cleansing : \
        1) Drop Extraneous Columns \
        2) Rename columns \
        3) Filter \
        4) Drop Null value \
        5) Drop duplicates \
        6) Fix data types 
5.  Explore Data with visualizations
6.  Conclusions and Visualizations
7.  Answers to the questions

# What is Fuel Economy ?
Excerpt from Wikipedia page on Fuel Economy in Automobiles: The fuel economy of an automobile is the fuel efficiency relationship between the distance traveled and the amount of fuel consumed by the vehicle. Consumption can be expressed in terms of volume of fuel to travel a distance, or the distance travelled per unit volume of fuel consumed.

# Datasets :
Fuel Economy Data This information is provided by the U.S. Environmental Protection Agency, Office of Mobile Sources, National Vehicle and Fuel Emissions Laboratory. Note that the datasets we'll be working with are slightly simpler than those found through the links below.

EPA Fuel Economy Testing : https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy \
DOE Fuel Economy Data : https://www.fueleconomy.gov/feg/download.shtml/ 

# Attribute Description :
    
Model Vehicle make and model \
Displ Engine displacement - the size of an engine in liters \
Cyl The number of cylinders in a particular engine \
Trans Transmission Type and Number of Gears \
Drive Drive axle type (2WD = 2-wheel drive, 4WD = 4-wheel/all-wheel drive) \
Fuel Fuel Type \
Cert Region* Certification Region Code \
Sales Area** Certification Region Code \
Stnd Vehicle emissions standard code (View Vehicle Emissions Standards https://www.epa.gov/greenvehicles/federal-and-california-light-duty-vehicle-emissions-standards-air-pollutants) \
Stnd Description* Vehicle emissions standard description \
Underhood ID This is a 12-digit ID number that can be found on the underhood emission label of every vehicle. It's required by the EPA to designate its "test group" or "engine family." This is explained more here https://www.epa.gov/vehicle-and-engine-certification/information-about-family-naming-conventions-vehicles-and-engines \
Veh Class EPA Vehicle Class \
Air Pollution Score Air pollution score (smog rating) \
City MPG Estimated city mpg (miles/gallon) \
Hwy MPG Estimated highway mpg (miles/gallon) \
Cmb MPG Estimated combined mpg (miles/gallon) \
Greenhouse Gas Score Greenhouse gas rating \
SmartWay Yes, No, or Elite \
Comb CO2* Combined city/highway CO2 tailpipe emissions in grams per mile \

"*" means Not included in 2008 dataset "**" means Not included in 2018 dataset
