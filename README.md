# vehicle_insurance_insights
Dataset from an vehicle insurance company with anonimized customers and no customer features

--- Introdution ---

This Jupyter Notebook presents the effort to gather, assess, analize, clean, prepare and model an insurance company data, available at https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction.

According to the source above, the data has information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc. It also informs whether the customer would be interested in vehicle insurance.

The main objective of this script is to answer the following business questions using the CRISP - Cross Industry Standard Process for Data Mining:

What is the percentage of interested people in vehicle insurance in our data?
Is there a specific public that are more interested in vehicle insurance compared to the others?
Is there a group that is less interested?
Can we predict if a person can be a potencial client using a machine learning technique?

The main business objective here is to understand who is more likely to acquire a car insurance so the marketing team can spend more energy in this group.

--- Libraries used ---

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn
- IPython

--- Files in the repository ---

- train.csv
This data has information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc. It also informs whether the customer would be interested in vehicle insurance.

- test.csv - not used
This data is similar to "train.csv", but without the interest column. Actually as this whole dataset was part of a hackathon challange, this archive was the one that the people shoud send back to evaluation.

- sample_submission.csv - not used
It was part of the hackathon submission.

--- Results ---
All the question made at the introduction were aswered.
The linear regression developed did work, but the r2 obteined (0,15) was not as high as I expected. Fell free to work on it in a better way and let me know how you did to teach me :)

Special thanks to Udacity and everyone that colaborates to StackOverflow. Thanks to Kaggle as well to make the data used available.

