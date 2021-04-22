# **Kickstarter-Analysis**

## **Overview**

The purpose of this project is to provide Louise with information about how to best set up her future funding campaigns to be successful. This project will allow me to show her what factors will make her fundraising campaign a triumph.

## **Analysis**

In order to provide Louise with the information for a successful funding campaign I used data based on the Funding Goals and Launch Dates of other campaigns.

#### **Analysis of Outcomes based on Launch Date**
The first step was to extract the data based on time of the year using the `YEAR()` function in Excel. A pivot table was created and the appropriate filters were applied. 
![Screen Shot 2021-04-17 at 11 33 24 PM](https://user-images.githubusercontent.com/81889167/115133389-d5dfda80-9fd5-11eb-9e84-709e38b187ff.png) 

A line chart was created to help visualize the data. 
![Theater_Outcomes_vs_launch](https://user-images.githubusercontent.com/81889167/115133455-5dc5e480-9fd6-11eb-86ae-23346286c428.png)
This visualization shows that campaigns that were initiated in the months of May and June had the most success and campaigns in December were not very successful.

#### **Analysis of Outcomes Based on Goals

I used the `COUNTIFS`function in Excel to find out how the funding goals affected the outcome of the campaigns based on the range of goals. 

![Screen Shot 2021-04-17 at 11 47 01 PM](https://user-images.githubusercontent.com/81889167/115133778-ce6e0080-9fd8-11eb-992e-833bf261786c.png)

I created a line graph to show that the higher the funding goal of a campaign the less likely it was to succeed. Goals with a goal amount less that $1000 were successful 76% of the time where campaigns with funding goals of more than $50000 were only successful %17 of the time. 
![Outcomes_vs_goals](https://user-images.githubusercontent.com/81889167/115133930-ce223500-9fd9-11eb-86a1-e3b9d99c47da.png)

#### **Challenges**

I definitely had issues working on this project as this is my first project of this nature. I overcame them in the following ways:

#### **Revision**

Sometimes going back and spotting errors were very obvious, other times I had to delete everything and start from scratch because I felt nothing I tried worked. Once I restarted I made sure to be more careful and made sure to note what mistakes I had made once I identified them. 

#### **Peer Support**

The best way I was able to overcome challenges was to ask for help! My new friend Naman was kind enough to point out a solution that was the simplest and I had been searching for a complex answer. Story of my life haha!

## **Results**

#### **Theater Outcomes Based on Launch Date**
I was able to draw two conclusions from my analysis from the information in Theater Outcomes by Launch Date. The first being that campaigns that were launched in the late Spring and early Summer months saw the most success. Secondly, campaigns that were launched in December were the least successful perhaps because it is the holiday season and people are using their money for other things.

#### **Funding Goals**
The conclusion that was drawn from the analysis based on funding goals is that the lower the funding amount goal the higher the percentage of success. 

#### **Limitiations**
The dataset did have limitations because there was a lot of information that was not useful to the purpose of the project and had to be filtered out. It would be helpful to use the Box and Whisker plots to help identify outliers that might be skewing data.
