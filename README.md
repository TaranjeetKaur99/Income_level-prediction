# Income_level-prediction
  The aim of my this project is to apply several machine learning algorithms to accurately model individuals' income, whether he makes more than $50,000 or not, using     data collected from the 1994 U.S. Census.
# Dataset
  The dataset that will be used is the Census income dataset, which was and contains about 199523 records and 42 features. My prediction task is to determine whether a     person makes his income over 50k a year.
# Provision
  Python

  scikit-learn / sklearn

  Pandas

  NumPy

  matplotlib
  
# About my dataset
Age : The age of an individual.

class_worker : A general term to represent the employment status of an individual.

det_ind_code : Information regarding Industry code of individual. 

det_occ_code : Description about Occupation code of individual.

education : The highest level of education achieved by an individual.

wage_per_hour : The hours an individual has reported to work per week

hs_college : Enrolled in educational institution last week on that year.

marital_stat : Marital status of an individual. Note: Married-civ-spouse corresponds to a civilian spouse while Married-AF-spouse is a spouse in the Armed Forces.

major_ind_code : Major industry code.

major_occ_code : Major occupation code.

race : Descriptions of an individual’s race.

hisp_origin : Hispanic origin.

Sex : The biological sex of the individual.

union_member : Member of a labor.

unemp_reason : Reason for unemployment.

full_or_part_emp : Full- or part-time employment status.

capital_gains : Capital gains for an individual (money gained outside of salary).

capital_losses : Capital loss for an individual (money lost outside of salary).

stock_dividends : Dividends from stocks.

tax_filer_stat : Tax filer status.

region_prev_res : Region of previous residence.

state_prev_res : State of previous residence.

det_hh_fam_stat : Detailed household and family status.

det_hh_summ : Detailed household summary in household.

mig_chg_msa : Migration code - change in MSA.

mig_chg_reg : Migration code - change in region.

mig_move_reg : Migration code - move within region.

mig_same : Live in this house one year ago.

mig_prev_sunbel : Migration - previous residence in sunbelt.

num_emp : Number of persons that worked for employer.

fam_under_18 : Family members under 18 

country_father : Country of birth father 

country_mother : Country of birth mother 

country_self : Country of birth 

Citizenship : Description about Citizenship of people.

own_or_self : Information regarding Own business or self-employed? 

vet_question : Fill included questionnaire for Veterans Admin

vet_benefits : Veterans benefits 

weeks_worked : Information about Weeks worked in the year.

Year : Description about Year of survey 

income_50k : Whether or not an individual makes more than 50,000 annually.




# Workflow
 Perform data cleaning using pandas library. Which includes replacing the missing values which is marked with '?' in this dataset.
 
 Make a Exploratory Data Analysis on the data using pandas.
 
 Visualize distributions and correlation of features using seaborn and pandas.
 
 Used the preprocessing technique.
 
 To balanced data by using imblearn technique.
 
 Make a classification model for the classification of income.
 
 Try different classifiers and compare the accuracy of all the classifiers.
