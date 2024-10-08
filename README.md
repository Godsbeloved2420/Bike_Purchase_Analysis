# Bike_Purchase_Analysis

## 1.0. Title
Bike Purchase Analysis using Python

## 2.0 Introductilon
### 2.1. Objectives: 

The aim of the analysis were to:

a) discover the relationship between average income of each gender and their bike purchase history.

b) determine the relationship between distance travelled by cummuters and bike purchase.

c) visualize the relationship between age bracket and bike purchase.


### 2.2. Context:

The dataset is made up of data collected by a company that deals on bike. The different fields contain different socio-demographic and bike purchase information of the customers. Which includes: ID,	Marital Status,	Gender,	Income,	Children,	Education,	Occupation,	Home Owner,	Cars,	Commute Distance,	Region,	Age,	Purchased Bike. The dataset contains two datatypes: strings and integers.

### 2.3. Data Sources

The primary source of data used here is bikedata.xlsx which was gotten as an excel file and it's an open source data which was given as a practice data. The following is the link to the dataset: 
https://docs.google.com/spreadsheets/d/1qzPm4m7N8K8KQcNwRcOZfbIZJ5YC0t0O/edit?usp=drive_link&ouid=106458428464023242528&rtpof=true&sd=true

## 3.0. Data Understanding

### 3.1. Data description
The dataset was gotten in a structured form and contains 1,026 rows and 13 columns. 

### 3.2. Exploratory data analysis (EDA)

Python (Google Colab) was implored in cleaning and analyzing the dataset. At the end of the analysis, we were able to:

a) discover the relationship between average income of each gender and their bike purchase history.

b) determine the relationship between distance travelled by cummuters and bike purchase.

c) visualize the relationship between age bracket and bike purchase.


## 4.0. Methodology
### 4.1. Data preprocessing

The dataset was imported into Google Drive then into Google Colab. The different libraries were also imported (Numpy, pandas, Matplotlib and Seaborn). The dataset was called 'file'.

#### Some of the steps taken in cleaning of the dataset includes:

a) removing of duplicates (file.drop_duplicates (inplace = True)

b) replacing 'M' and 'S' in the Marital Status column of the dataset with 'Married' and 'Single' respectively (file['Marital Status']=file['Marital Status'].replace(['M','S'],['Married','Single']). 

c) replacing 'M' and 'F' in the Gender column with 'Male' and 'Female' respectively (file['Gender']=file['Gender'].replace(['M','F'],['Male','Female']).

d) 

e) descriptive statistics (mean, median, standard deviation) were conducted on the numerical columns (data.describe()).

f) checking and removing of duplicates from the dataset (data.duplicated().sum())

### 4.2. Assumptions:
Customers preferred cars produced by ‘Ford’ manufacturer compared to those produced by other manufacturers due to its average price and fuel efficiency.

## 5.0. Analysis
### 5.1. Results:

#### Car model with the highest resale value compared to its initial price

![picture 1](https://github.com/user-attachments/assets/ad471307-1f21-4328-84a5-8f89f01185a4)

#### Counting the number of missing values in each column 

![picture 2](https://github.com/user-attachments/assets/e8320966-5b8b-46ed-aa90-67d2083086da)

#### Dropping the columns with null values

![picture 3](https://github.com/user-attachments/assets/09b088c7-a038-4260-8003-88f1e2c21082)

#### Distribution of Car price in the dataset

![picture 4](https://github.com/user-attachments/assets/9209bd83-292b-4ec3-8652-ee0abc0d0ec3)

#### Correlation of numerical values in the dataset

![picture 5](https://github.com/user-attachments/assets/33409225-ba9e-4ad0-84ad-1627f109f63f)

#### Relationship between Price and Latest launch year

![picture 6](https://github.com/user-attachments/assets/c6fe8082-64c6-4364-8f56-41a45c9897c8)

### 5.2. Interpretation/key findings: 

From the result, it can be seen:

•	‘Ford’ is the Manufacturer with the highest average sales volume while ‘Porsche’ is the manufacturer with the lowest average sales volume.

•	‘Mercedes-B’ is the manufacturer with the highest car price in the dataset.

•	There’s a strong correlation between ‘Horsepower’ and ‘Power perf factor’ where p=0.99.

•	The highest increase in Car price was in 2011.

•	‘Ford’ is mostly purchased by customers.

•	Car model with the highest resale value is Carrera Cabrio. 

•	‘Impala’, ‘Monte Carlo’ and ‘CLK Coupe’ are the top three (3) fuel efficient cars with an engine above 2.5 liters.

•	The ‘Lexus’ model with the highest ‘Horsepower’ is ‘Viper’ with 450 Horsepower.

## 6.0. Conclusion
### 6.1. Summary of finding:

•	The dataset came as a structured dataset which contained 157 observations and 16 columns. 

•	The dataset contains integers, strings and floats.

•	The ‘Year resale value’ column had the highest null value (36) in the dataset.

•	The dataset had no duplicates but contains a total of fifty-one (51) null values. 

•	‘Ford’ is the Manufacturer with the highest average sales volume while ‘Porsche’ is the manufacturer with the lowest average sales volume.

•	‘Mercedes-B’ is the manufacturer with the highest car price in the dataset.

•	There’s a strong correlation between ‘Horsepower’ and ‘Power perf factor’ where p=0.99.

•	The highest increase in Car price took place in 2011.

•	‘Ford’ is most popular Car Manufacturer.

•	‘Carrera Cabrio’ is the Car model with the highest resale value.

•	‘Impala’, ‘Monte Carlo’ and ‘CLK Coupe’ are the top three (3) fuel efficient cars with an engine above 2.5 liters.

•	The ‘Lexus’ model with the highest ‘Horsepower’ is ‘Viper’ with 450 Horsepower.

## 7.0. Acknowledgement

I acknowledge PSP Analytics for this great platform for learning. I want to sincerely our facilitators (Mr. Okon Prince, Mr. Joseph Edet, Mr. Joseph Elijah and Mr. Zion) for providing the dataset that was used for this analysis and for their tireless efforts to ensure we get the best from the training. Google Colab was employed in this analysis.

