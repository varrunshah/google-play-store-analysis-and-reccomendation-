# Google Play Store analysis and recommendation
The main idea behind making this project is to analyze the play store apps based on their categories, rankings and ratings. The 4 basic questions-
1) What is the ratio of paid vs free apps? 
2) What percentage of applications had have over million and billion downloads?
3) Which application category is most popular?
4) Is there any correlation between ratings and installs

This project will take a toll on all of the above questions and thus answering them in the most reasonable manner 
# Data 
The dataset used for this project was taken from [kaggle](https://kaggle.com).  On acquiring the dataset, we saw that there was a need for us to the data exploration along with data munging. There were a lot of null values which needed to be replaced, removing unnecessary columns, converting all the app sizes to MB and more. There are various applications that can be serached by the user based on their categories, ratings, installs, price etc. Therefore to clean the data properly we had to perform certain necessary steps and hence gained the desired result. Data cleaning and formatting is an important part in making quality predictions and and models

# System Requirements
The basic system requirement for this project were-

- Python 3.6 and above 
- Jupyter notebook

# Libraries
The different range of ibraries used for this project are-
- pandas 
- numpy
- matplotlib
- seaborn
- sklearn 

After importing all these libraries, we just dived into for our very own analytical exploration of the project.

# Execution
This project is done with the help of [jupyter notebook](https://github.com/varrunshah/google-play-store-analysis-and-recommendation/blob/main/google%20play%20store%20project.ipynb). On opening the notebook you will be delighted to see the various analysis made and our job to overcome with all the answers with great endurance. The notebook describes all the functionalities done by us hoping to make it very clear with less or no confusion at all.

# Challenges 
The challenges faced during the making of this project was majorly on the data. Since most of the data was not as simple as expected, we had to face the problem of data inconsistency and its redundancy. Some of the inconsistencies included formatting of colums with null values or unecessary data, changing the size of the applications from M to MB, also python is not quite able to encounter the "+" sign with respect to the downloads made by a particular application.

# Insights
Following thread will help to give an overview of the key findings made in the project-

Ratio of paid apps vs free apps-
![Result1](key%20diagrams/paid%20vs%20free.png?raw=true)

Percentage of applications having more of a million or billion downloads-
![Result2](key%20diagrams/downloads.png?raw=true)

Popular applications available based on their category-
![Result3](key%20diagrams/popular.png?raw=true)

Number of applications downloaded based on ratings vs category-
![Result4](key%20diagrams/boxplot.png?raw=true)

