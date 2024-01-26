# PRODIGY_DS_02
 Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice on a dataset from Kaggle . Explore the relationships between variables and identify patterns and trends in the data.


Steps and Learnings:

1️⃣ Data Loading:
I started by loading the dataset into a pandas DataFrame using the read_csv function.

2️⃣ Data Cleaning:
To ensure high data quality, I addressed missing values in the dataset. Using the isnull and sum functions, I identified the number of missing values for each column. I then filled missing values for the 'Age' column with the median age and for the 'Embarked' column with the mode. Additionally, I dropped unnecessary columns such as 'PassengerId', 'Name', 'Ticket', and 'Cabin' that wouldn't contribute to the analysis.

3️⃣ Exploratory Data Analysis (EDA):
In this crucial step, I explored relationships between variables and uncovered patterns and trends within the data.

Overall Survival Rate:
I calculated the survival rate by analyzing the 'Survived' column and visualized it using a bar chart.

Survival Rate by Pclass:
I grouped the data by 'Pclass' and calculated the survival rate for each class. The results were visualized using a bar chart, providing insights into the relationship between passenger class and survival.

Survival Rate by Sex:
Similarly, I grouped the data by 'Sex' and calculated the survival rate for each gender. A bar chart was created to visualize the impact of gender on survival.

Age Distribution:
I explored the age distribution of passengers using a histogram, enabling me to understand the age demographics aboard the Titanic.

Fare Distribution:
I further investigated the fare distribution using another histogram, shedding light on the ticket price ranges among passengers.
