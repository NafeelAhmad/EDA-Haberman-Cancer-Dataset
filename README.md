# EDA-Haberman-Cancer-Dataset

## Exploratory Data Analysis : Haberman's Survival

Dataset contains cases from study conducted on the survival of patients who had undergone surgery for breast
cancer. It is collected from the study of University of Chicago's Billings Hospital between year 1958 to
1970.

More info about the Dataset :-
It has four features including class label.
Column of age have different age group people.
Year columns tells in which year operation had done.
Auxillary lymph nodes tells no. of nodes vary from women to women.
Survival status 1 shows no. of person survived 5 years or more & survival status 2 shows no. of person died
within 5 years.


Observation After Performing EDA:
Patients with more nodes are less likely to survive.
Patients having zero nodes did surive but some also died. So lymph nodes are not accurate for survival.

Overall Conclusion:
From Scatter And Pair - Plots ---
1. From Scatter Plot, Approximately 99% women have survived having lymph node = 0 and age group of 51 to
59.
2. Pair PLot is not much useful but Lymph nodes is better option than the rest.

From PDF's and CDF's ---
1. Age of 30-32 have survived.
2. Year is not good choice to analyze this data.
3. When disease was detected with less lymphs nodes (0 to 4), person was survived mosstly. But this didn't
mean having more lymph nodes (greater than 5) caused death to patient.

Other Points ---
1. This dataset is imbalanced as it does not contain equal data points for each class.
2. Graph in this dataset is not linearly seperable for each class And It also shows immense overlapping
thatswhy very difficult to predict the class.
3. lymph nodes is more useful feature than opeartion year & age for classification.
4. But need more useful feature to analyze the data because operation year, age & lymph nodes are not so much useful.
5. We can't build simple model by using if else condition.
6. We need of more advanced technique to analyze this dataset
