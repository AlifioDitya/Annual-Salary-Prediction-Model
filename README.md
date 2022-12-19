# Annual Salary Prediction
This is a personal machine learning project to predict whether income exceeds $50K/yr based on an Adult Census Income dataset provided by UCI Machine Learning on Kaggle [1].

## Dataset
The dataset contains features such as [2]:
- **Age**: Describes the age of individuals. Continuous.
- **Workclass**: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- **fnlwgt**: Continuous.
- **education**: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
- **education-num**: Number of years spent in education. Continuous.
- **marital-status**: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
- **occupation**: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
- **relationship**: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- **sex**: Female, Male.
- **capital-gain**: Continuous.
- **capital-loss**: Continuous.
- **hours-per-week**: Continuous.
- **native-country**: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
- **salary**: >50K,<=50K

## Method
Prediction is made using machine learning techniques specifically the Logistic Regression Model to classify the income class of a person based off of the feature values described above.
Evaluation is then conducted with the model having 84.7% accuracy.

## Reference
- [1] UCI Machine Learning (2016). Kaggle. https://www.kaggle.com/datasets/uciml/adult-census-income
- [2] Aditi Mulye (2018). Kaggle. https://www.kaggle.com/code/aditimulye/adult-income-dataset-from-scratch 
