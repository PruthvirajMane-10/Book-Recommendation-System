📚 Book Recommendation System

Machine Learning–Powered Personalized Book Recommender

A production-ready Book Recommendation System built using Popularity-Based and Collaborative Filtering techniques and deployed as a Flask web application.
The system delivers popular recommendations for new users (cold start) and personalized book suggestions based on user interaction data.

🚀 Key Features

✅ Handles cold-start users using popularity-based recommendations

✅ Personalized recommendations via Collaborative Filtering

✅ Book similarity computed using Cosine Similarity

✅ Clean and responsive Flask web interface

✅ End-to-end real-world ML workflow (data → model → deployment)

🧠 Recommendation Approaches

1️⃣ Popularity-Based Recommendation

- Used when user interaction history is unavailable.

- Books are ranked using:

- Average rating

- Number of user votes

Best for: New users and homepage recommendations

2️⃣ Collaborative Filtering (Item-Based)

- Provides personalized recommendations based on user-selected books.

Workflow:

- User–item interaction matrix (pivot table)

- Cosine similarity between books

- Recommend top similar books

- Best for: Returning users with interaction history

🛠️ Tech Stack

- Programming Language: Python

- Libraries: Pandas, NumPy, Scikit-learn

- Web Framework: Flask

- Frontend: HTML, CSS

- Model Storage: Pickle (.pkl)

📁 Project Structure
Book-Recommendation-System/

│

├── app.py                  # Flask application

├── model.ipynb             # Data preprocessing & model building

├── requirements.txt

├── README.md

├── .gitignore

│

├── templates/

│   ├── index.html           # Homepage (popular books)

│   └── recommend.html       # Personalized recommendations

│

├── static/

│   └── style.css

│

└── data/

    ├── popular.pkl          # Popularity-based model
    
    ├── pt.pkl               # Pivot table
    
    ├── books.pkl            # Book metadata
    
    └── similarity_scores.pkl# Cosine similarity matrix

⚙️ How to Run Locally

Step 1: Clone the Repository
git clone https://github.com/<your-username>/book-recommendation-system.git
cd book-recommendation-system

Step 2: Install Dependencies
pip install -r requirements.txt

Step 3: Run the Flask App
python app.py

Step 4: Open in Browser
http://127.0.0.1:5000/

📌 Use Cases

📖 Online book stores

📚 Digital libraries

🎯 Personalized reading platforms

🧪 Recommendation system learning projects

🔮 Future Enhancements

- User authentication & profile-based recommendations

- Hybrid recommendation system (content + collaborative)

- Cloud deployment (AWS / Render / Railway)

- Enhanced UI/UX and performance optimization

👨‍💻 Author

Pruthviraj Mane

Aspiring Data Scientist | Machine Learning Engineer

📌 Passionate about building real-world ML systems

⭐ Support

If you find this project useful, give it a star ⭐ — it really helps and motivates!

