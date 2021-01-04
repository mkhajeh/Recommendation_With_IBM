# Table of Contents

1. [Project Description and Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Contributors](#Contributors)
6. [Licensing & Copyright](#licensing)
7. [Acknowledgements](#Acknowledgements)
---
## Project Description and Motivation<a name="motivation"></a>
In this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. In order to determine which articles to show to each user, I performed a study of the data available on the IBM Watson Studio platform.
This project is divided in the following tasks.

**I. Exploratory Data Analysis**

Before making recommendations of any kind, I will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data I want to work with throughout the rest of the project. I completed EDA in this section.

**II. Rank Based Recommendations**

To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

**III. User-User Based Collaborative Filtering**

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. I implemented User-User Based Recommendation in this section.

**IV. Matrix Factorization**

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using my decomposition, I got an idea of how well I can predict new articles an individual might interact with. I finally discussed which methods I might use moving forward, and how I might test how well my recommendations are working for engaging users.


-----

## Installation<a name="installation"></a>
Here is the list of main libraries that I have used for this project:
* Numpy
* Pandas
* pickle
* matplotlib

more detailed about modules and functions used from each of these libraries could be found in *required libraries* section of python files.

The code should run with no issues using Python versions "3.8.3".

---
## File Descriptions <a name="files"></a>
There are two initial **csv** files available for this project:
* articles_community.csv
* user-item-interactions.csv

These two csv files has been saved in *data* folder of current directory. all the codes required for this project has been written in *Recommendation_with_IBM.ipynb* notebook in main directory.

---
## Results <a name="results"></a>

 The final outcome of this project are the codes written for different recommendation techniques which could be easily run to find list of recommendations for each specific user (and also for the user who are new to IBM platform).


---
## Contributors <a name="Contributors"></a>
Mehdi Khajeh
* email: <khajeh@ualberta.ca>
* cellphone: 403-667-8048
---
## License & Copyright <a name="licensing"></a>

&copy; Mehdi Khajeh 2021
Licensed under [MIT License](License)

---
## Acknowledgements <a name="Acknowledgements"></a>
Thanks to Udacity for defining this great project. As a result of this project, I forced myself to comprehensively review **Descriptive and Inferential Statistics** and **Linear Algebra** first.  In addition, I learned more about **Singular Value Decomposition (SVD)** and **Funk-SVD** Machine Learning Algorithms** in more details.

---
