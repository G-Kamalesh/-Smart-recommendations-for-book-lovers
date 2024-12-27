# A Personalized Book Recommendation System
This is an intelligent recommendation system designed to connect readers with books they’ll love. Built using collaborative filtering techniques, this project leverages user ratings and preferences to suggest personalized book recommendations.

# Features
📚 Recommendation Engine: Provides book recommendations based on user reading patterns using the Unsupervised K-Nearest Neighbors (KNN) algorithm.                                      
🛠️ Data Preprocessing: Handles large-scale, sparse datasets efficiently with techniques like filtering, deduplication, and pivot table creation.                                        
📈 Optimized Performance: Utilizes cosine similarity and sparse matrix representations for scalable and fast computations.                                                            
📊 Evaluation: Evaluated using a test case.

# Dataset

The project uses a dataset containing:

User ratings: Ratings range from 1 to 10.                                                                                                                                            
Books: Unique ISBNs, titles, and authors.                                                                                                                                              
Interactions: Over 1 million user-book interactions.

# Tech Stack

Python (pandas, NumPy, scikit-learn)                                                                                                                                               
Data Handling: Sparse matrix operations with csr_matrix                                                                                                                        
Recommendation Algorithm: Unsupervised KNN

# How It Works

**Data Preparation:**

Filters users with at least 200 ratings and books with at least 100 ratings.                                                                                                  
Resolves duplicate user-book interactions with unique ISBNs.

**Model Building**

Uses cosine similarity to identify similar users or books.                                                                                                                  
Constructs a recommendation engine using KNN.

**Recommendation:**

Generates personalized book suggestions based on user preferences.

**Evaluation:**

Assesses the quality of recommendations with a test case.

# Future Enhancements

Integration of content-based filtering for hybrid recommendations.                                                                                                                     
Improved scalability for handling larger datasets.                                                                                                                                       
Interactive user interface for enhanced user experience.

# Contact
[Linkedin](www.linkedin.com/in/g-kamaleashwar-28a2802ba)               
[Porfolio](https://kamalesh-portfolio.streamlit.app)
