# Healthcare_Analytics

The healthcare sector has long been an early adopter of and benefited greatly from technological advances. These days, machine learning plays a key role in many health-related realms, including the development of new medical procedures, the handling of patient data, health camps and records and the treatment of chronic diseases. 

## Challenge
MedCamp was started because the founders saw their family suffer due to bad work life balance and neglected health.

MedCamp organizes health camps in several cities with low work life balance. They reach out to working people and ask them to register for these health camps. For those who attend, MedCamp provides them facility to undergo health checks or increase awareness by visiting various stalls (depending on the format of camp). 

```The Process:```
MedCamp employees / volunteers reach out to people and drive registrations.
During the camp, People who “ShowUp” either undergo the medical tests or visit stalls depending on the format of health camp.
 
 ```Other things to note:```
Since this is a completely voluntary activity for the working professionals, MedCamp usually has little profile information about these people.
For a few camps, there was hardware failure, so some information about date and time of registration is lost.
MedCamp runs 3 formats of these camps. The first and second format provides people with an instantaneous health score. The third format provides information about several health issues through various awareness stalls.

```Favorable outcome:```
For the first 2 formats, a favourable outcome is defined as getting a health_score, while in the third format it is defined as visiting at least a stall.
You need to predict the chances (probability) of having a favourable outcome.

## Dataset
Train.zip contains the following 6 csvs alongside the data dictionary that contains definitions for each variable

1. Health_Camp_Detail.csv – File containing Health_Camp_Id, Camp_Start_Date, Camp_End_Date and Category details of each camp.

2. Train.csv – File containing registration details for all the test camps. This includes Patient_ID, Health_Camp_ID, Registration_Date and a few anonymized variables as on registration date.

3. Patient_Profile.csv – This file contains Patient profile details like Patient_ID, Online_Follower, Social media details, Income, Education, Age, First_Interaction_Date, City_Type and Employer_Category

4. First_Health_Camp_Attended.csv – This file contains details about people who attended health camp of first format. This includes Donation (amount) & Health_Score of the person.

5. Second_Health_Camp_Attended.csv - This file contains details about people who attended health camp of second format. This includes Health_Score of the person.

6. Third_Health_Camp_Attended.csv - This file contains details about people who attended health camp of third format. This includes Number_of_stall_visited & Last_Stall_Visited_Number.
###### Link: https://datahack.analyticsvidhya.com/contest/janatahack-healthcare-analytics/#ProblemStatement

## Evaluation Criteria
The evaluation metric for this hackathon is ROC-AUC Score.

## LeaderBoard

No. of Registered: 14458

Public Leaderboard rank: 227

Private Leaderboard rank: 237

https://datahack.analyticsvidhya.com/contest/janatahack-healthcare-analytics/#LeaderBoard
