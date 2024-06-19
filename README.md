# Description 
This is an analysis of data focused on predicting obesity levels in individuals, using 
information about their dietary habits and physical health. The dataset contains a lot of features 
that possibly are related to obesity levels, such as dietary habits, physical activity, family history, 
and social-demographic characteristics. 23% of the dataset was collected directly from users 
through a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas using a 
web platform. 77% of the dataset was created synthetically using the Weka tool and the SMOTE 
filter. 

# Dataset source
https://www.kaggle.com/datasets/muhramasaputra/obesity-based-on-eating-habits-and-physical-cond/data

# Dataset description

The data contains 19 attributes and 2111 records.

- Gender: is 1 if a respondent is male and 0 if a respondent is female.
- Age: is a respondent’s age in years.
- family_history_with_overweight: is 1 if a respondent has family member who is or was overweight, 0 if not.
- FAVC: is 1 if a respondent eats high caloric food frequently, 0 if not.
- FCVC: is 1 if a respondent usually eats vegetables in their meals, 0 if not.
- NCP: represents how many main meals a respondent has daily (0 for 1-2 meals, 1 for 3 meals, and 2 for more than 3 meals).
- CAEC: represents how much food a respondent eats between meals on a scale of 0 to 3.
- SMOKE: is 1 if a respondent smokes, 0 if not.
- CH2O: represents how much water a respondent drinks on a scale of 0 to 2.
- SCC: is 1 if a respondent monitors their caloric intake, 0 if not.
- FAF: represents how much physical activity a respondent does on a scale of 0 to 3.
- TUE: represents how much time a respondent spends looking at devices with screens on a scale of 0 to 2.
- CALC: represents how often a respondent drinks alcohol on a scale of 0 to 3.
- Automobile, Bike, Motorbike, Public_Transportation, and Walking: indicate a respondent’s primary mode of transportation. Their primary mode of transportation is indicated by a 1 and the other columns will contain a 0.
- NObeyesdad: is a 1 if a patient is obese and a 0 if not.