# Recommendations-with-IBM
### Introduction
For this project we analyze the interactions that users have with articles on the IBM Watson Studio platform, 
and make recommendations to them about new articles you think they will like. 
Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

<img width="573" alt="image" src="https://user-images.githubusercontent.com/81413089/126683745-50fc5585-f61e-417d-a8b5-1417f4a7587c.PNG">

### Tasks Performed : 

#### * Exploratory Data Analysis
Before making recommendations of any kind, we need to explore the data we are working with for the project.

#### * Rank Based Recommendations
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. 
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

#### * User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms 
of the items they have interacted with. These items could then be recommended to the similar users. 
This would be a step in the right direction towards more personal recommendations for the users.

#### * Matrix Factorization
Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, 
we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with.

### File Descriptions :
* Recommendations_with_IBM.ipynb: Jupyter notebook containing main implementation and analysis.
* Recommendations_with_IBM.html: A copy of Recommendations_with_IBM.ipynb in html format.
* data/user-item-interactions.csv: Csv file with user-item interactions.
* data/articles_community.csv: Csv file with indexed items.

Click [here](https://github.com/rachit1010/Recommendations-with-IBM) to check the "Recommendation of engine" repository. 

