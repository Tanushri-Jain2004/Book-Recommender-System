📚 **Book Recommender System**
📘 **Overview**

The Book Recommender System is a machine learning web application built using Flask and Jupyter Notebook.
It recommends books to users based on popularity, user similarity, or content-based filtering.
The project demonstrates how data science and web development can be combined to deliver an intelligent recommendation experience.

🎯 **Objectives**

Build a system that suggests books users might enjoy.

Implement and compare different recommendation approaches.

Deploy the trained model using a Flask web interface for real-time predictions.

🧠 **Recommendation Techniques**

Popularity-Based Recommendation:
Suggests the most popular books (based on ratings and number of reviews).

Collaborative Filtering:
Recommends books based on similar users’ preferences using cosine similarity or nearest neighbors.

Content-Based Filtering (Optional):
Suggests books similar in genre, author, or description to those the user has liked.

🧾 **Dataset Information**

Dataset Name: Book Recommendation Dataset (from Kaggle or other open source)

Files Used:

Books.csv – Contains book titles, authors, and publication details.

Users.csv – Contains user information.

Ratings.csv – Contains user ratings for books.

Key Columns:

Book-Title, Book-Author, User-ID, Rating

⚙️ **Tech Stack**
Component	Technology
Programming Language	Python
Data Analysis	Pandas, NumPy
Machine Learning	Scikit-learn
Web Framework	Flask
Frontend	HTML, CSS, Bootstrap
Development	Jupyter Notebook
🧩 **Project Structure**
📦 **Book-Recommender-System**
├── app.py                # Flask app file
├── templates/
│   ├── index.html        # Homepage
│   ├── recommend.html    # Recommendation page
├── static/
│   ├── style.css         # CSS styling
├── models/
│   ├── similarity.pkl    # Precomputed similarity matrix
│   ├── books.pkl         # Books dataset pickle
│   ├── popular.pkl       # Popular books data
├── notebook/
│   ├── Book_Recommender.ipynb  # Jupyter notebook for data exploration and model building
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation

🧮 **Example Features**

Search for your favorite book and get similar recommendations.

View top 50 popular books based on ratings.

Interactive and minimal web interface built with Flask.

📈 **Sample Output**

“If you liked Harry Potter and the Philosopher’s Stone, you might also enjoy The Hobbit or Percy Jackson.”

Dashboard shows top-rated and most-reviewed books.

📓 **Notebook Includes**

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Similarity matrix computation

Model export using pickle

Integration with Flask backend
