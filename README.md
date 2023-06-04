# Airbnb's program to predict the country of reservation for new subscribers

## Overview
#### 📚 Data: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings
#### 🫶 Purpose: predict in which country a new user will make his or her first booking.
#### 👩🏻‍💻 Datasets Used: train_users_2.csv, test_users.csv <br>

## Data Preprocessing
#### Describe the preprocessing steps taken for the numerical(age, sighnup_flow) and categorical data(gender, language). (Fills a null value and removes unfilled rows)
##### If the age is less than 10 years old or more than 90 years old, it was considered an abnormal value and dropped
<img width="316" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/29474ab7-aafc-4cd3-b446-fa9a5597d7d1">
<img width="316" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/13938025-0e87-47e6-a059-75e01a543cbb">
<img width="324" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/d73e21b1-8b3d-4321-a034-eef39e948a80">


### Scaling
#### the numerical data was preprocessed by scaling (MinMax, Robust, Standard)
<img width="720" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/4aa50284-6818-448c-815a-9aa1bb21f819">


### Encoding
#### the categorical data was preprocessed by encoding (OneHot, Ordinal, Label).<br>
<img width="364" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/fd7048b8-0993-4f19-86d4-9e77a70ce7fd">
<img width="434" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/bf1f7d40-fb34-4729-891d-133c9c4853fd">
<img width="193" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/5aec8d78-492d-4363-b788-6f55d9eaff5b">
<img width="193" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/900f5536-24b4-40e1-8544-76d34cb98516">


## Data Visualization
#### Visualization based on data frames processed for outliers
<img width="296" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/ee0f811b-1d96-469b-a5b1-ca72490ad141">
<img width="337" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/6c03e652-0f12-4438-bb23-44cf9feeb769">
<img width="297" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/97f9b8da-a3a7-4fb6-812d-871e0a16e25d">

## Modeling
#### Describe the models used (Logistic Regression and Decision Tree) 
<img width="358" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/2faf68ec-ffb7-4d32-8e61-601de6bec387">
<img width="273" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/17c34114-72c5-4a6c-8ccc-b2fa13acea2e">

## Model Visualization
<img width="412" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/bad175a8-8d6d-4bfb-8daf-53e2dad6415a">

## Evaluation
### Use k fold cross validation to find the optimal k value
<img width="453" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/f85c3d4d-ee22-4cb4-b9f4-5529922ec035">
<img width="453" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/482f7a29-b1f6-4851-8ad3-4d2737d92f80">

### Use confusion matrices to visualize the results of classification tasks and evaluate the performance of models
#### Logistic Regression
<img width="428" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/d8fdaa94-9f2b-4870-91eb-fcf2977a25b7">

#### decision tree
<img width="435" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/6a51c0b5-02b4-4e79-b822-d35265967020">


## Best 5 combination
#### Extract the top 5 combinations of all combinations considering 3 encoders (One-hot, Ordinary, Label) + 3 Scaling (MinMax, Standard, Robust) + hyperparameters 
<img width="405" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/6beb55c6-90b2-4338-bcd1-d295436e99ae">

## Analysis
#### Analyze critical features in predicting destinations through modeling
<img width="293" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/17f575e3-6683-454d-b511-52df0ec5f667">
<img width="196" alt="image" src="https://github.com/Chae0510/Airbnb_NewUserBooking/assets/85086390/09999948-d2fa-4a6f-8abf-a749e2c7e8af">

## Usage
#### It can be used to interpret other data because it has carried out an end-to-end process that includes all the steps, including data collection, preprocessing, modeling, evaluation, and data analysis results analysis.


