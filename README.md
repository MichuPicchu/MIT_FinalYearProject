# Final Year Project

![Screenshot](readme_images/search_bar.png)


## Description :

Note: Here, I have removed the frontend components, and only included the backend (parts that I have worked on) due to plagiarism.

### Back-end setup (Python, FlaskAPI, SQLlite)

Here is the database architecture, implemented with a cloud database.

![Screenshot](readme_images/database_design.png)

### Recommender System (Item-based collaborative filtering)

The aim of the recommendation system was to automatically recommend restaurants to users that they have never been to that they would likely like.

The implementation of the recommendation system was challenging since there were many new concepts and equations that required understanding, as well as trying to manipulate our own database to fit into the equation.

The recommendation system was designed on the Item-based collaborative filtering model, with the Peason’s Coefficient Correlation Method, with the number of minimum restaurants set to 2. This was chosen as it removes any offsets given the ratings, also since it is the most popular method for similar applications.

Firstly, the model required a matrix of p x p dimensions (where p is the number of restaurants). The matrix would represent a similarity matrix, giving a similarity score (between -1 and 1) for each restaurant. The similarity score would be based on the ratings given by the users to the restaurant.

![Screenshot](readme_images/similarity_formula.png)

Then with this similarity matrix, we were able to calculate and predict the score with this formula

![Screenshot](readme_images/recommendation_score.png)

The final result :

![Screenshot](readme_images/recommender_page.png)

### Unit testing (Python unittest library)


## Website Preview:

Login/register page :

![Screenshot](readme_images/register_page.png)

Restaurant Page:

![Screenshot](readme_images/restaurant_page.png)

Profile Page:

![Screenshot](readme_images/profile_page_1.png)

Community Page:

![Screenshot](readme_images/community_page.png)

