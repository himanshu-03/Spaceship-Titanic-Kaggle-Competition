## Spaceship Titanic
### Predict which passengers are transported to an alternate dimension



## 📌 Dataset Description
The task is to `predict` whether a passenger was `transported` to an alternate dimension during the Spaceship Titanic's collision with the spacetime anomaly. To help us make these `predictions`, we are given a set of personal records recovered from the ship's damaged computer system.

<br>

## 📌 File and Data Field Descriptions

- **train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.**

  - `PassengerId` - A unique Id for each passenger. Each Id takes the form `gggg_pp` where `gggg` indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
  
  - `HomePlanet` - The planet the passenger departed from, typically their planet of permanent residence.
  
  - `CryoSleep` - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
  
  - `Cabin` - The cabin number where the passenger is staying. Takes the form `deck/num/side`, where `side` can be either `P` for Port or `S` for Starboard.
  
  - `Destination` - The planet the passenger will be debarking to.
  
  - `Age` - The age of the passenger.
  
  - `VIP` - Whether the passenger has paid for special VIP service during the voyage.
  
  - `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
 
  - `Name` - The first and last names of the passenger.
  
  - `Transported` - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
  
- **test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data.**
  - The task is to predict the value of Transported for the passengers in this set.
  
- **sample_submission.csv - A submission file in the correct format.**
  
  - `PassengerId` - Id for each passenger in the test set.
  
  - `Transported` - The target. For each passenger, predict either True or False.

<br>

## 👀 Screenshots

<img src = "/assets/1.png">
<img src = "/assets/2.png">
<img src = "/assets/3.png">
<img src = "/assets/4.png">
<br>

## 📓 Overview

| Machine Learning Models Applied            | Accuracy |
| ----------------- | ------------------------------------------------------------------ |
| Light Gradient Boosted Machine (LGBM) | 80.68% |
| Extreme Gradient Boosting (XGBoost) | 80.52% |



<br>

## 👉 Application

Predict the probability of user clicking the ad which is shown to them on the partner websites
for the next 7 days based on historical view log data, ad impression data and user data. Since
every individual may have a different view of your brand, stories or slogans can resonate with
everyone differently. Through target marketing, you can better understand each customer's
needs and create a marketing campaign that targets a specific audience, so you can meet their
expectations.

<br>

## ✍️ Authors

- [Himanshu Agarwal](https://github.com/himanshu-03)

<br>

## 🔗 Links


<a href='https://colab.research.google.com/drive/13Iuik9gy9bEb8XbxViz-E3XCYvtaQtey?usp=sharing' target="_blank"><img alt='Google Colab' src='https://img.shields.io/badge/Google_Colab-100000?style=for-the-badge&logo=Google Colab&logoColor=FFA200&labelColor=000000&color=FFFFFF'/></a>
<a href='https://www.kaggle.com/code/hiimanshuagarwal/spaceship-titanic/notebook' target="_blank"><img alt='Kaggle' src='https://img.shields.io/badge/KAGGLE-100000?style=for-the-badge&logo=Kaggle&logoColor=20beff&labelColor=black&color=FFFFFF'/></a>

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


<br />

## 🪪 License
This project follows the [MIT LICENSE](https://choosealicense.com/licenses/mit/).

<br />

<div align="center">
<h3> Connect with me<a href="https://gifyu.com/image/Zy2f"><img src="https://github.com/milaan9/milaan9/blob/main/Handshake.gif" width="50px"></a>
</h3> 
<p align="center">
    <a href="https://www.github.com/himanshu-03" target="_blank" rel="noreferrer"><img alt="Github" width="37px" src="https://github.com/himanshu-03/himanshu-03/raw/main/assets/socials/github.png"></a> &nbsp&nbsp&nbsp
    <a href="https://www.linkedin.com/in/agarwal-himanshu" target="_blank"><img alt="LinkedIn" width="35px" src="https://cdn.iconscout.com/icon/free/png-512/free-linkedin-189-721962.png?f=webp&w=256"></a> &nbsp&nbsp&nbsp
    <a href="https://twitter.com/hiimanshu_03" target="_blank"><img alt="Twitter" width="35px" src="https://freelogopng.com/images/all_img/1690643777twitter-x%20logo-png-white.png"></a> &nbsp&nbsp&nbsp
    <a href="https://www.instagram.com/_._hiimanshu_._" target="_blank"><img alt="Instagram" width="35px" src="https://github.com/himanshu-03/himanshu-03/raw/main/assets/socials/instagram.png"></a> &nbsp&nbsp&nbsp
    <a href="mailto:himanshuaaagarwal2002@gmail.com" target="_blank"><img alt="Gmail" width="35px" src="https://github.com/himanshu-03/himanshu-03/raw/main/assets/socials/gmail.png"></a>&nbsp&nbsp&nbsp
<p align="right">(<a href="#top">Back to top</a>)</p>
</p> 
