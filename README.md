# Recommendations Engines with IBM
This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

##  Installations
This project requires Python 3.x and the following Python libraries installed:
- [Nltk](https://www.nltk.org/)
- [Pandas](http://pandas.pydata.org)
- [Progressbar](https://pypi.org/project/progressbar/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Summary:
The project contains the following tasks:
- Exploratory Data Analysis: This part is for data exploration.
- Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
- User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
- Content Based Recommendations:  Using  NLP skills, I developed a content-based recommendation system.
- Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with .    

## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Acknowledgments
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [IBM](https://dataplatform.cloud.ibm.com/) for providing the data.
