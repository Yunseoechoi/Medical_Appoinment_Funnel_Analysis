# Medical_Appoinment_Funnel_Analysis
Create synthetic data for medical appointments. Configure which ML type and data type has highest accuracy to generate reliable data. 

DAY 1: Found medical appointment data from OpenML to import to juypter notebook. Started the set up to compare the different data learning types. Will try to compared between GaussianCouplaSynthesizer, CTGANSynthesizer, and TVAESynthesizer.

DAY 2: Finished setting up synthetic and training data to compare. Have to next figure out creating baseline data to compare both data to. 
DAY 3: Realized that with non-neumerical data, cannot set baseline with randomforestclassifer. Will first try creating baseline with DummyClassifier and then move on to other models to compare which would be the best model. Will have the encode data for the later models that needs to be only in neumerical data. 