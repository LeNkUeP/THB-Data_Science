
## EA 1 - Data Science Introduction Exercises (15 points)

1. Ask a same question both in ChatGPT and Gemini, then compare the results. -- 5pt
2. You are a CEO from a business/startup with around 50 employees. You are considering to hire one or several data positions, what kind of data employee are you going to hire and why. Please describe the business, product/service first, and explain the reason of hiring data experts. (you can also not hire anyone)  -- 10pt

## EA 2 - Python Exercises (25 points)

Q1: Write 2 python function to get the indices of the sorted elements of given lists and compare the speed. one is without numpy package and the other is with numpy. (raise a error message if the input is null or not numerical) -- 13pt

List 1: [23, 104, 5, 190, 8, 7, -3]
List 2 : []
List 3 : random generate 1000000 integers 

Q2: Do the following exercise in a Jupyter Notebook (a GitHub Link would be the best): -- 12pt
Load the countries.csv directly via URL import into your panda data frame!
Display descriptive statistics for the numerical column (count, mean, std, min, 25%, 50%, 75%, max) HINT: describe
Show the last 4 rows of the data frame.
Show all the rows of countries that have the EURO
Show only name and Currency in a new data frame
Show only the rows/countries that have more than 2000 GDP (it is in Milliarden USD Bruttoinlandsprodukt)
Select all countries where with inhabitants between 50 and 150 Mio
Calculate the GDP average (ignore the missing value)
Calculate the GDP average (missing value treated as 0)
Calculate the population density (population/area)  of all countries and add as new column
Sort by country name alphabetically
Create a new data frame from the original where the area is changed: all countries with > 1000000 get BIG and <= 1000000 get SMALL in the cell replaced!
Send me a PDF or a link to GitHub / GitLab, etc.

The idea is: DevEnvironment + your passion!

## EA 3 - Feedback from Dr. Tran's talk (10 points)

Please write your feedback, idea, or summary of the talk from Dr. Huy Tran.
and write down if you are willing to share this feedback to the speaker (Y/N)

## EA 4 - R Exercise (20 points)

Please follow the steps below

1. Download Rstudio & R
2. Use Rstudio(Posit) to create rmarkdown file
3. Running the following analysis from Rmarkdown

download pacakge ggplot2
import the data("iris")
use the ggplot for all the tasks below
make a scatter plot with x-axis: Sepal.Length and y-axis: Sepal.Width, and the species should be shown in different colors
add regression line for the previous plot with the whole dataset (regardless of the species)
calculate the Pearson correlation for this plot
make the boxplot for Petal.Width with 3 species separately in the x-axis in different colors
make the histogram for Petal.Width with 3 species separately in x-axis in different colors
run the t-test of Petal.Width between setosa and virginica, and give the conclusion if the width is a statistically significant difference between 2 species

4. knit to html
You need to submit 2 files, one is the .Rmd file and the other is .html file
The github/Gitlab link is acceptable as well.

## EA 5 - Feedback from Mr de Gail's talk (10 points) 

Please write your feedback, idea, or summary of the talk from Mr. Jérémy de Gail. Please indicate if you would like to share the feedback with the speaker anonymously (Y/N)

## EA 6 - Probabiliy (30 points + 10 bouns points)

1. with a unfair 6-side dice, the probability of point 2 is twice than point 1, probability of point 3 is triple than point 1, and so on. What is the expected value and variance of this dice? -8 pt

2. write a python / R function to simulate the Goat-car door open problem (Monty Hall problem) 100 times. write the conclusion and what do you think? -15pt

Input: number of expiernment
output:     1. the success time if you change
                 2. the success time if you do not change 
3. I have a bag in front of me containing a 6-sided (with number 1 to 6) and a 12-sided dice (with number 1 to 12). My friend pulls one out at random, rolls it once, and tells me that the number is 5. What is the probability that my friend pulled out the 6-sided die? -7pt

4. Romeo and Juliet would like to meet. Romeo will pick a random time between 9:00- 10:00 and Juliet pick a random time between 9:30 - 10:00  independently and waits for the other for 10 minutes and leave if they don't see the other. What is the probability that the two will meet? - bonus 10pt

## EA 7 - Data Clean & Statistics (35 points) 

Following is research data for investigating the disease situation in a given area. This research recruits volunteers who must be at least 40 years old.

There are two files containing the patient's information

Patient_information:

Patient_ID: numeric the patient id with 7 digits
Sex: string Male or Female
Age: numeric The Age of recruitment
BMI: numeric Body Mass Index, should be between 15-60
Smoking_status: string Never, Previous, current, Prefer not to answer
Disease: factor 1 means disease, 2 means healthy

Hosptial Visit:
Patient_ID: numeric the patient id with 7 digits
VisitDate: Date, the date of the patient's visit hospital. the data is collected from the year 1950 to 2023

Task : Data Clean & EDA

Replace missing BMI values with the median BMI for the corresponding gender.
Perform a sanity check on all columns in both files, and remove any samples that do not pass.
Calculate the number of visits each patient made since 1/1/2020. If the VisitDate is missing, it indicates no visits during this period.
Create a summary table and/or chart showing the number of visits for each month (irrespective of the year).
add a new column "age group " to split the age to 5 categories:  40-49, 50-59, 60-69, and above 70)
Merge the two files to include the columns: Patient_ID, Sex, Age, BMI, Smoking_status, Number_of_visits, Disease and age group


Task: Statistics (you don't need to check the model assumption in this exercise)

Compare the BMI between the healthy and control groups using a box or violin plot.
Examine if the proportion of smoking status differs between the healthy and control groups.
Analyze the relationship between smoking status and the number of hospital visits, separately for the disease and healthy groups, and for the overall population.
Determine if the number of visits is higher in the disease group compared to the healthy group.
Calculate the disease prevalence (number of sick  / total number population) across different age groups  in our dataset, and test if the prevalence is different across the group

please write a comment for each task, not only run the statistical test without an explanation

## EA 8 - ML Introduction Exercise ( 40 points + 3 extra points) 

### Objective

Use the fish dataset to predict the weight of the fish based on various features.



#### Features:

- **Species**: The species name of the fish.

- **Length1**: Vertical length in cm.

- **Length2**: Diagonal length in cm.

- **Length3**: Cross length in cm.

- **Height**: Height in cm.

- **Width**: Diagonal width in cm.

- **Weight**: Weight of the fish in grams (g).



### Data Preparation

- Clean the dataset if necessary before analysis. 



### Task 1

1. Split the dataset randomly into training (70%) and testing (30%) sets. 

2. Apply the following models:

   - Linear Regression 

   - Random Forest 

  

3. Calculate RMSE (Root Mean Squared Error) and R2
 (Coefficient of Determination) on the test set. 

4. Visualize the predictions by plotting y_pred vs y_real and compare the performance of the models.

5. Provide your opinion on which metric, RMSE or R2, is more appropriate in this case.

### Task 2

1. Change the training-test split to ensure that each species has 70% of its samples in the training set and 30% in the test set.

2. Repeat steps 2, 3, 4, from Task 1.



### Comparison

- Compare the results obtained from Task 1 and Task 2.



### Extra Point

- point out which parameters can be adjusted in this exercise to improve model performance. (dont need to run analysis again)

## EA 9 - Classification Exercise (40 points + 3 point extra)

There are 2 files training and test

This dataset is designed to understand the factors that lead a person to leave their current job for HR research. By model(s) that uses the current credentials, demographics, and experience data you will predict the probability of a candidate looking for a new job or will work for the company, as well as interpreting affected factors on employee decision.

Note:

The dataset is imbalanced.
Most features are categorical (Nominal, Ordinal, Binary), some with high cardinality.
Missing imputation can be a part of your pipeline as well.
Features

city_ development _index : Developement index of the city (scaled)

gender: Gender of candidate

relevent_experience: Relevant experience of candidate

enrolled_university: Type of University course enrolled if any

education_level: Education level of candidate

major_discipline :Education major discipline of candidate

experience: Candidate total experience in years,

company_type : Type of current employer

last_new_job: Difference in years between previous job and current job

training_hours: training hours completed

target: 0 – Not looking for job change, 1 – Looking for a job change


Task1 Data clean, imputation

1. in experience, replace >20 to 21; <1 to 1, and convert this as a numerical column
2. in last_new_job, replace >4 to 5; never to 0, and convert this as a numerical column
3. If the column is categorical, impute the missing value as its mode. If the column is numerical, impute the missing value as its median

Task2 Classification

1. Build a classification model from the training set ( you can use any algorithms)
2. generate the confusion matrix and calculate the accuracy, precision, recall, and F1-score on training set. 
3. Applying the model in the test set and generating the prediction
4. generate the confusion matrix from the test set and calculate the accuracy, precision, recall, and F1-score
5. compare the results between the training and test set

The data is modifed , but you can get some help from Kaggle

Extra point: think about what kind of the method can increase the performance (does not need to run )

## EA 10 - Clustering Exercise (30 points)

Objective:
To categorize the countries using socio-economic and health factors that determine the overall development of the country.

Problem Statement:
HELP International has been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively.  Hence, your Job as a Data scientist is to categorize the countries using some socio-economic and health factors that determine the overall development of the country.

Data

Country information

Task:

1. use K-means clustering and Hierarchical clustering to cluster the country into groups.

please choose the number of the cluster in a rational reason

2. use PCA to reduce the dimension to 2d, and visualize the cluster from K-means and Hierarchical clustering respectively

3. please write the suggestion to CEO about the country you suggest


It is from Kaggle, but the data has been modified.
