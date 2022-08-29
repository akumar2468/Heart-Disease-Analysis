# Heart-Disease-Analysis

This project uses machine learning and R to determine whether an individual has heart disease or not. The machine learning aspect of this project utlizes supervised machine learning because information about the output is known. Since this is a classification problem, there are two outputs: 1 as an individual having heart disease and 0 as an individual not having heart disease.

In this dataset, there are 14 features (columns), which also includes the target. The dataset includes the following variables:

- slope_of_peak_exercise_st_segment (type: int): the slope of the peak exercise ST segment, an electrocardiography read out indicating quality of blood flow to the heart
- thal (type: categorical): results of thallium stress test measuring blood flow to the heart, with possible values normal, fixed_defect, reversible_defect
- resting_blood_pressure (type: int): resting blood pressure
- chest_pain_type (type: int): chest pain type (4 values)
- num_major_vessels (type: int): number of major vessels (0-3) colored by flourosopy
- fasting_blood_sugar_gt_120_mg_per_dl (type: binary): fasting blood sugar > 120 mg/dl
- resting_ekg_results (type: int): resting electrocardiographic results (values 0,1,2)
- serum_cholesterol_mg_per_dl (type: int): serum cholestoral in mg/dl
- oldpeak_eq_st_depression (type: float): oldpeak = ST depression induced by exercise relative to rest, a measure of abnormality in electrocardiograms
- sex (type: binary): 0: female, 1: male
- age (type: int): age in years
- max_heart_rate_achieved (type: int): maximum heart rate achieved (beats per minute)
- exercise_induced_angina (type: binary): exercise-induced chest pain (0: False, 1: True)

We can observe that when we load the data, there are no null values in the dataset. The data type for our variables are numeric, indicating that the data does not need to be changed into dummy variables.

