# Diabetes Predictor 
Objective is topredict whether the patient has diabetes or not. using Azure Learning Tool is used to design the model. AU’s Health department considers this is the right time for them to do a good usage of the dataset they were able to build by providing an open diabetes predictor to the community.it should serve as an advisor for triage purposes.
with the information provided by the patient (Age, Gender, Body Mass Index, Blood Pressure, Serum 1-6, and current diabetes level – Y) the engine should be able to predict what the diabetes rate should look like in 12 months from the date of the inquire.
the engine should be able to provide further recommendations to patients projected to be running over the acceptable threshold that separates diabetic people from non-diabetic people.
it should be consumed exposed through APIs so whatever external channel could take advantage of it. The bot is the preferred way to consume the engine, as far as AU’s health team would like to begin with.

# Project Description
Diabetes prediction has to be built from scratch as Microsoft Cognitive Services doesn’t offer an specialized API for for that purpose.
There is a recommendation piece in there, which could be a good fit for Recommendations API in Azure (we need to validate that).
There is, obviously, a Dataset involved. It does mean we’re gonna need some storage capability for that purpose.
There is also a need for compute Meaning that we need a place for us to run the models we’re going to build.
Once we’re satisfied with the results our model is returning, we need, somehow to publish it in the format of Restful API, so that different channels can consume.
AU’s Health department would like to have a Bot serving as interface between patients and the predictor in Azure.

# Azure Technology Used:
1- Azure Machine Learning
2- Azure Open Datasets
3- Azure Piplines

# Resources Available in the Model
Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skin fold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: Diabetes pedigree function

Age: Age (years)

Outcome: Class variable (0 or 1)
