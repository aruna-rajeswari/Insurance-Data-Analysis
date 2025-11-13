Insurance Data Analysis

OBJECTIVE
The goal of this project is to perform exploratory data analysis (EDA) on a medical insurance dataset to uncover patterns and relationships that affect insurance premium charges. Ultimately, the insights gained will help build a predictive model for estimating medical costs based on demographic and health-related attributes.

DOMAIN
Healthcare & Insurance Analytics

DATASET DESCRIPTION
Source: insurance.csv
Columns:
•	age: Age of the individual
•	sex: Gender (male/female)
•	bmi: Body Mass Index (health indicator)
•	children: Number of children covered by insurance
•	smoker: Smoker or non-smoker
•	region: Residential area (northeast, northwest, southeast, southwest)
•	charges: Insurance premium paid

STEP-BY-STEP PROCESS
•	Step 1: Import Libraries and Load Data
o	Used pandas, matplotlib, seaborn, and numpy to load and explore the dataset.

•	Step 2: Basic Data Checks
o	Verified shape and data types.
o	Ensured no missing values were present in the dataset.

•	Step 3: Exploratory Data Analysis (EDA)
o	Count Plots
	Sex: Roughly equal distribution between males and females.
	Smoker: Fewer smokers than non-smokers, but they pay much higher premiums.
	Region: Fair distribution across all regions.

o	Pair Plot (sns.pairplot(df, hue='smoker'))
	Age vs Charges: Charges increase with age, especially for smokers.

	BMI vs Charges: Smokers with high BMI pay the most.
	Children vs Charges: Weak correlation; smokers still pay more.
	Smokers consistently show higher charges across most numerical features.

o	Scatter Plots
	Age vs Charges (colored by smoker): Steep upward curve for smokers.
	BMI vs Charges: Higher BMI = higher cost, especially for smokers.

o	Heatmap
	Used to visualize correlation between numeric features.
	charges correlated most strongly with smoker, followed by age and bmi.

•	Step 4: Trend Analysis
o	Smokers vs Age vs Charges: Linear regression plot showed a sharp increase in premium with age for smokers, while non-smokers showed a gradual increase.

KEY INSIGHTS
•	Smoking status is the most significant factor influencing insurance charges.
•	Age and BMI also play important roles in premium costs.
•	Children and region have little to no significant impact on charges.
•	Smokers are at higher risk, hence face much higher premiums, especially as they age or if they have high BMI.

CONCLUSION
The analysis reveals that lifestyle factors like smoking and health indicators like BMI significantly affect insurance costs. These findings support the hypothesis that premiums are adjusted based on health risks. This EDA provides a solid foundation for building a predictive model using features like age, BMI, and smoker status to estimate insurance charges.
