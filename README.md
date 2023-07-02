# SmokersCollabFilter 🚬: Smoking Recommendations with Item-Item CF.
# [still-in-progress💻]

## **About** ℹ️

#### This repository contains a personal project of a collaborative filtering-based recommendation system focused on analyzing smoking habits and providing personalized recommendations.

## **What is a Collaborative filtering (CF) Recommendation System** ❔

#### A Recommendation System is an algorithm that uses large amounts of data to suggest additional products to consumers, providing recommendations that are relevant to other users similar to them. The final results can be based on various criteria, such as previous purchases by other consumers, demographic information, etc.

#### Such recommendation systems are used by companies like Amazon and Netflix to make appropriate recommendations to their users, with the help of artificial intelligence since we are talking about a fairly large amount of data.

## **The Idea** 💡

#### This idea came from our family business that I assisted in during my school and undergraduate years. For many years, my parents ran a kiosk in Thessaloniki. During my studies in the Department of Applied Informatics, I took the course " Knowledge Discovery from Databases" in which we learned about item-item collaborative filtering techniques.

#### As a non-smoker, I found it interesting that often several of our clients would change cigarette or tobacco brands. Therefore, I thought about starting to collect data from specific customers on what cigarettes-tobaccos they have tried and how they would rate them in order to create such a system in the future.

## **Data Collection** 📋 📲

### Currently, I am implementing the Recommendation System I am trying to enrich the pre-existing data by using a questionnaire via Google Forms which is available [here](https://forms.gle/mxZ2vkbJ2C2VeuHB8).

#### While we still ran the family business the collection of the necessary data was done with a simple questionnaire (in Greek) like the one below:
![](https://raw.githubusercontent.com/christakakis/SmokersCollabFilter/main/docs/questionnaire.png)

## **Additional Details** 📌

#### The system leverages item-item collaborative filtering techniques to identify similarities between users based on their smoking history, ratings and preferences. By analyzing past smoking behaviors and user responses from questionnaires, the system generates recommendations for alternative smoking products. This project aims to offer insights into smoking patterns and assist users in making informed decisions towards new rated smoking products.

### The final format of the table created from the answers of the questionnaires should look like this: 

<table>
  <caption align="center"><b>Item-Item CF Ratings Table</b></caption>
  <thead>
    <tr>
      <th align="center"><b> </b></th>
      <th align="center"><b>User_1</b></th>
      <th align="center"><b>User_2</b></th>
      <th align="center"><b>User..</b></th>
	    <th align="center"><b>User_N</b></th>
    </tr>
  </thead>

  <tbody>
    <tr>
       <td align="center"><b>Tobacco Brand_1</b></td>
       <td align="center"">4</td>
       <td align="center"><b> </b></td>
       <td align="center"">...</td>
	     <td align="center""><b> </b></td>
    </tr>
    <tr>
       <td align="center""><b>Tobacco Brand_2</b></td>
       <td align="center""><b> </b></td>
       <td align="center"">1</td>
       <td align="center"">...</td>
	     <td align="center""><b> </b></td>
    </tr>
    <tr>
       <td align="center""><b>Tobacco Brand_3</b></td>
       <td align="center"">3</td>
       <td align="center"">5</td>
       <td align="center"">...</td>
       <td align="center"">4</td>
    </tr>
    <tr>
       <td align="center""><b>Tobacco Brand ..</b></td>
       <td align="center"">...</td>
       <td align="center"">...</td>
       <td align="center"">...</td>
       <td align="center"">...</td>
    </tr>
    <tr>
       <td align="center""><b>Tobacco Brand_M</b></td>
       <td align="center"">2</td>
       <td align="center""><b> </b></td>
       <td align="center"">...</td>
       <td align="center"">2</td>
    </tr>
  </tbody>
</table>

### **NOTE** 🚭

##### **Please do not embrace smoking, it is harmful to your health.** This project focuses on analyzing smoking habits and providing recommendations, but it is important to note that the intention is not to promote smoking or encourage its use. Smoking poses significant health risks and can have detrimental effects on individuals and society. The aim of this project is to provide insights and support to individuals who may be seeking information related to smoking habits or alternatives. Prioritize your health and make informed decisions.
