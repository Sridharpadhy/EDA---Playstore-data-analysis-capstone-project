# EDA---Playstore-data-analysis-capstone-project

![image](https://github.com/Sridharpadhy/EDA---Playstore-data-analysis-capstone-project/assets/120051156/1da1e853-12d1-4954-96b9-fd4728ae7350)


FILES DETAILS:
1. Tableu Presentation - It contain tableau dashboard files created after EDA.
2. Two Files of CSV - The raw data provided us for EDA.
3. PPT - It containing all the detail of project explained in PPT
4. Collab NB - This the collab File where all the Explorartory analysis has done.
5. Technical Documnent - Technical summary documentation provided.
6. Summary - Summary of whole project is been added over here.
   

                                                          Play Store App Review Analysis
Mobile apps are everywhere. They are easy to create and can be lucrative, because of these two factors, more and more apps are being developed. In this notebook, we will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google play store   across different categories 
The Google play store app dataset consists of enormous data that can be used to create effective insights. There are various key factors that play a major role in the success & engagement from the user’s end. Our problem statement is quite inevitable in comparison with the present Google Play store App market. To , explore and analyze datasets are provided, one with basic information and the  other with user reviews for the respective app  and discover all the key factors responsible for app engagement and success.
Upon doing several pieces of research it can be seen that every day around 3000+ apps is being added to the play store library. Therefore enormous datasets & variety of insights can be concluded for business improvements.


In this EDA project we were provided with two datasets ::

1.	Playstore.csv -> contains all the details of the applications of Google Play. There are 13 features that describe a given app.
They are :
•	App :- Name of the App
•	Category :- Category under which the App falls.
•	Rating :- Application's rating on playstore
•	Reviews :- Number of reviews of the App.
•	Size :- Size of the App.
•	Install :- Number of Installs of the App
•	Type :- Whether the App is free/paid
•	Price :- Price of the app (0 if it is Free)
•	Content Rating :- Appropriate Target Audience of the App.
•	Genres:- Genre under which the App falls.
•	Last Updated :- Date when the App was last updated
•	Current Ver :- Current Version of the Application
•	Android Ver :- Minimum Android Version required to run the App
________________________________________
2.	User_reviews.csv -> contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features
•	Sentiments (Positive, Negative, Neutral)
•	Sentiment Polarity
•	Sentiment Subjectivity

Steps wE did ::
At first, we break down the datasets
•	By importing necessary library classes
•	Then by  basic inspection of dataset. 
•	Then data cleaning and  clean that attributes which have not to be useful and  Replace all the Null values with the Average of their Columns or with not null values.
•	Then followed by Data manipulation and handling duplicate data by checking unique values, converting the data types to similar objects, removing special characters as the analysis demands & making the entire dataset ready for analyzing & plotting actionable insights.
•	As the data become ready for analyze we went into the visualization steps.

Some insights on which we worked are as follows:

1.	Getting the average Rating of the Apps.
2.	Checking the count of application in each category
3.	Getting the number of installs in each Category
4.	Checking Corelation between the variables
5.	Getting App Size Distribution
6.	Getting the number of installs with respect to the size of the application
7.	Lets see the major Type of app distribution in playstore.
8.	Lets see the apps dependence on size and type and it effect on rating too.
9.	Review sentiments in all the app dataset.
10.	Let's see a more depth understanding of sentiment Polarity and Subjectivity.
11.	Does sentiments Polarity is proportional to sentiments subjectivity .




Results ::

- With more than 1 billion active users in 190 countries around the world, Google Play continues to be an important distribution platform to build a global audience. This makes the hell lot of competition in App market.

- And also we can say that before starting any kind of exploration the data cleaning play a vital role in result and accuracy.

- As we all can see the many observations and conclusion that arise from the data visualization and how visualizations make anything interesting with the graphs, plots, chart or maps.

- Which simplify the data and can be easily understand the role of the data and their elements in the diverse world of play store.

- As per the graphs visualizations shown above, most of the trending apps (in terms of users' installs) are from the categories like GAME, COMMUNICATION, and TOOL even though the amount of available apps from these categories are twice as much lesser than the category FAMILY. The trending of these apps is most probably due to their nature of being able to entertain or assist the user. Besides, it also shows a good trend where we can see that developers from these categories are focusing on the quality instead of the quantity of the apps.

- Other then this also can be say that mostly the app has higher number of user installs or review gives the app a good rating and mostly all the apps are around the rating of 4 (8000 apps).Also the size and price of the app create a minute difference but not majorly effect the app with good rating, review even if their app size are high. But due to free in charges we get the higher number of user installs and ratings.

- Also, it can be seen from the chart that the sentiments play important role and maximum number of sentiment which are positive around (64.1 %) lies between subjectivity 0.4 to 0.7. From this, we can conclude that the maximum number of the audience give reviews to the applications, according to their experience.

As, we can see that, why exploring data is important before starting to build ML models.
As a conclusion, we learnt that the current trends in the Android market are mostly from these categories which assisting, communicating or entertaining apps.
