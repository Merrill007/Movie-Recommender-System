# Movie-Recommender-System
## Movie Recommender System Project Documentation

### Project Overview:

**Goal:** Build a movie recommender system using Python.

### Steps Taken:

1. **Data Collection:**
   - **Dataset Used:** MovieLens 100K dataset containing 100,000 movie ratings from users.
   - **Rationale:** Chosen for its diverse user ratings across various movies.

2. **Data Preprocessing:**
   - Loaded data using Pandas for manipulation and analysis.
   - Inspected data to understand structure and content.
   - Checked for missing values (none found in this dataset).
   - No merging of dataframes was required.

3. **User-Item Interaction Matrix:**
   - Created a matrix representing user preferences for movies.
   - Rows: Users, Columns: Movies, Values: User ratings.
   - **Rationale:** Provides structured representation for collaborative filtering.

4. **Similarity Calculation (User-User Collaborative Filtering):**
   - Calculated user similarity using cosine similarity metric.
   - **Rationale:** Identifying users with similar taste is crucial for collaborative filtering.

5. **Movie Recommendations:**
   - Implemented a function to generate movie recommendations for a given user based on similarity to other users.
   - **Rationale:** Provides personalized recommendations based on user preferences.

### Results:

- Successfully generated movie recommendations for User 1 based on the user-item interaction matrix and user similarity.

### Challenges Encountered:

- Initially, there was difficulty retrieving the recommended movie titles due to an indexing issue. This was resolved by adjusting the code to directly extract the titles from the movies dataframe.

### Recommendations for Further Steps:

1. **Model Evaluation (Optional):**
   - Evaluate the performance of the recommender system using metrics like Mean Absolute Error (MAE) or Root Mean Square Error (RMSE) on a test set.

2. **Deployment (Optional):**
   - Consider building a web application to allow users to interact with the recommender system.

3. **Iterate and Refine:**
   - Based on evaluation results or user feedback, iterate on the model or data preprocessing steps to improve performance.

### Conclusion:

- Successfully built a movie recommender system using collaborative filtering. The system provides personalized movie recommendations based on user ratings and similarity with other users. This project serves as a foundation for further enhancements and applications in recommendation systems.
