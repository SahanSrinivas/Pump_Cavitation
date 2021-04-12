# Pump_Cavitation
Performance Monitoring and Prediction of Cavitation in Centrifugal Pumps.

# What is Cavitation?
Cavitation is the formation of bubbles or cavities in liquid, developed in areas of relatively low pressure around an impeller. The imploding or collapsing of these bubbles trigger intense shockwaves inside the pump, causing significant damage to the impeller and/or the pump housing.

# Reasons for Pump Cavitation
When Net Positive Suction Head Available (NPSHA)  is less than Net positive suction head required (NPSHR) which is NPSHA < NPSHR
Minimum required flowrate across the pump which is pump spillback. There must be vendor or licensor recommended flowrate of pump which should be recycled across 
Pump vibrations. When vibrations increases there will be cavitation in pumps which caused impeller damage.

![image](https://user-images.githubusercontent.com/36400481/114375682-8c8d2680-9ba2-11eb-9d14-ee5e71bf9654.png)

# If left untreated, pump cavitation causes

1. Failure of pump housing
2. Destruction of impeller
3. Excessive Vibration - Bearing failure
4. Higher than necessary power consumption
5. Decreased flow and/or pressure

# Independent and Dependent Variables for Pump Cavitation

# Independent Variables:

Suction Pressure – Converted Suction Pressure to Suction Head (ft)
Suction Temperature – Converted Vapor Pressure of Water to Vapor Pressure Head (ft)
Velocity Head – ft – Assumed a 3-inch Pipeline and maximum amount of flow is 400 gpm
Gauge Height – ft –  Assumed Gauge Height of 1 ft
Friction Loss – ft – Friction loss of 3-inch pipe at 400 gpm
NPSHA = Suction Head – Vapor Pressure Head + Velocity Head + Gauge Height – Frictional Head

# Dependent Variables

NPSHR = Which we will get from vendor.
Other additional variables which can be considered are:
Pump Rotational Speed (RPM)
Pump Spillback
Pump Vibrations


# List of models used for prediction analysis

1. Random Forrest
2. Logistic Regression
3. Support Vector Classification
4. Naive-Baies 
5. Dummy Classifier
