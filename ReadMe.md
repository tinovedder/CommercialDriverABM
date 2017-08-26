Commercial Driver Safety. ABM - SD Hybrid model
Mike, Yorghos, Alexander Dumais

Terminology:
ES_Building - Trucks stops with Environmental Safety facilities (proper food and workout facility). <Name subject to change?>
Destination - The current destination for the trucker.
travelStateChart - the statechart that determines Driver mobility within the model.
weightStateChart - the state charts that categorizes the Drivers' BMI classification
SD (System Dynamics) Component - The Stock and Flow chart that controls Driver Weight over time.

This model simulates Truck drivers in the United States and the affects of that proper health facilities at truck stops can have on their weight over time. It has State charts for Traveling states and Weight states (NormalAndUnderweight, Overweight, Obese), as well as an SD component for changing weight based on healthy choices when at truck stops.

Current state of the model: 
-Full mobility implemented using a GIS map for routing.
-SD component not yet imp,emented with proper values
-No logic implemented for Driver interactions with ES_Building facilities.
