
# project 3 - recommendations
Udacity: Project 3

The project is about recommendation engines.The project follow the following structure:-
- Exploratory Data Analysis
- Rank Based recommendations
- user-user based collaborative filtering
- Content based recommendations
- Matrix factorization

Different functions are created to recommend articles to users in IBM platform
The following recommendations are covered
* Rank based recommendations
* Collaborative filtering recommendation
* Content based recommendation
* Matrix factorization(SVD) recommendation

The following main funtions were created in the notebook
* get_top_article- to filter topp articles from given dataframe
* get_top_article_id - to map article title with article id
* create_user_item_natrix - to create a matrix given dataframe with interactions
* find_similar_user - to filter siler users to the provided uder_id
* get_article_names - to map article_id with article name
* etc, more can be checked on notebook.

The following libraries were used
* pandas
* numpy
* matplotlib
* TfidfVectorizer from sklearn
* cosine_similarity from sklearn

The data was provided by Udacity.
