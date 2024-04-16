
# Medical Cost Prediction

This project predicts the medical cost of patients based on demographic factors, lifestyle-related
information, health status, insurance plan type, family medical history, distance to the nearest
hospital, primary care physician visits etc... The predicted price can help hospitals to optimize resource
allocation, healthcare planning, and patient support services.


## Data Sources

The dataset used in this project was obtained from Hospital ABC. It contains information about patients' demographics, lifestyle, health status, and medical expenses etc. The dataset also includes attributes
such as age, gender, BMI, smoking status, region, as well as additional information like occupation, exercise frequency, chronic conditions, and more.



## Preprocessing Steps

The raw dataset underwent preprocessing steps, including imputing missing values using mean and mode, hadling outliers by replacing them with median, encoding categorical variables (e.g., Sex, Region), and scaling. The dataset was then split into training and testing sets.
## Model Selection

I experimented with several regression models including Linear Regressor, Random Forest Regressor, Gradient Boosting Regressor and AdaBoost Regressor.
## Evaluation

The performance of each model was evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error(MAE) and R-squared (R2) score. The Random Forest Regression model outperformed the other models, achieving an RMSE of 5.57,MAE of 2.85 and an R2 score of 0.90 on the test set.
## Project Findings and Insights

### Demographic Insights:

The dataset predominantly comprises males in the "sex" column, and the majority of patients are non-smokers.
Most patients are married, and the income level tends to be low for the majority.
### Occupational and Educational Insights:

The distribution of white-collar and blue-collar jobs is similar, with the majority engaged in other occupations.
Majority of patients have completed high school education, while only a minority have college degrees.
### Health Behavior Insights:

Unhealthy dietary habits and high alcohol consumption are prevalent among the majority of patients.
However, most patients report good quality sleep and low levels of stress.
### Healthcare Access and Usage Insights:

A significant portion of patients are employed, and access to healthcare is challenging for many.
Many patients lack adequate social support, and a majority report a negative impact of environmental factors on health.
Genetic predisposition is prevalent, and a significant proportion of patients have comorbidities.
### Medication and Treatment Insights:

The majority of patients do not use prescription medication, and "Yes" is the predominant response in the medication adherence column.
While access to telemedicine is available for many, a notable portion reported its unavailability.
### Medical Charges Insights:

Medical charges tend to increase with age, indicating higher costs for older individuals.
There's a direct relationship between BMI levels and medical charges, with higher BMI correlating with increased healthcare expenses.
## Recommendations

### Improve Telemedicine Access:

Make it easier for people to use telemedicine services by offering more options and explaining how to use them.
### Promote Healthy Eating:

Encourage people to eat healthier foods by sharing information and providing resources about good nutrition.
### Provide Social Support:

Offer help and companionship to those who need it, so they don't feel alone or isolated.
### Raise Awareness for Healthy Living:

Spread the word about healthy lifestyle choices through campaigns. This includes quitting smoking, learning about nutrition, and managing stress.
### Enhance Healthcare Access:

Make it easier for everyone to get medical help by offering more telemedicine services and addressing issues like transportation and costs.
### Support People Socially:

Set up programs and resources to help people who feel lonely or don't have family support.
### Improve the Environment:

Make changes to the environment, like improving air quality and adding green spaces, to make people healthier.
### Offer Genetic Advice:

Provide counseling and screening for people with a family history of certain diseases to help them manage their health better.
### Educate People About Health:

Teach people how to understand health information and make good decisions about their health.
### Manage Multiple Health Problems:

Create plans to help people with more than one health problem get the care they need and avoid getting sicker.
### Preventive Care:

Encourage regular check-ups and vaccinations to stop people from getting sick in the first place.
### Financial Help:

Find ways to help people pay for medical bills if they don't have much money. Help people understand their insurance options and get the right coverage for their medical needs.
### Use Data to Decide:

Look at information about patients to figure out who needs help the most and where to spend money to help them.
## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fathima-thanseeha)


