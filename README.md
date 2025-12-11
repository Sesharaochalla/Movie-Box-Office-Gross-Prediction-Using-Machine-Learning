*****🎬 Movie Box Office Gross Prediction*****

A machine learning project that predicts movie box office revenue using data-driven features such as genres, cast, crew, budget, popularity, and more.
This project includes full EDA, model training, and a Flask web application for real-time predictions.

**📌 Features**

📊 Exploratory Data Analysis (EDA) with insights from TMDB datasets

🧹 Data preprocessing (cleaning, feature engineering, scaling)

🤖 Machine Learning Model (trained to predict movie revenue)

🧠 Encoded categorical features such as genre using label encoders

🌐 Flask-based web app for making predictions via user input

📁 Pre-trained model and encoders stored as .pkl files

🖼️ Frontend templates for user-friendly UI (HTML/CSS)

**📂 Project Structure**
Movie-Box-Office-Gross-Prediction-Using-Machine-Learning/
│
├── static/                        
├── templates/                      
│
├── EDA.ipynb                       
├── main.ipynb                    
│
├── app.py
│
├── revenue_prediction_model.pkl    
├── genre_label_encoder.pkl        
├── scaler.pkl                     
│
├── tmdb_5000_movies.csv            
├── tmdb_5000_credits.csv         
│
└── README.md                     

**🚀 How It Works**
1. Data Preprocessing

Handled missing values

Extracted genre, cast, crew details

Converted budget and revenue to proper numeric types

Scaled numerical features

Encoded categorical features

2. Model Training

Tried multiple machine learning algorithms

Selected the best-performing model (saved as .pkl)

Evaluated using metrics such as MAE, RMSE

3. Web App (Flask)

Users provide:

Movie Genre

Budget

Popularity

Runtime

Cast / Crew details (optional depending on implementation)

The Flask app loads the ML model and returns:
➡️ Predicted Box Office Revenue

**▶️ Running the Project**
1. Clone the repository
git clone https://github.com/your-username/Movie-Box-Office-Gross-Prediction-Using-Machine-Learning.git
cd Movie-Box-Office-Gross-Prediction-Using-Machine-Learning

2. Install dependencies
pip install -r requirements.txt


If you don’t have a requirements file, let me know—I can create one.

3. Run the Flask app
python app.py

4. Open in browser
http://localhost:5000

**📊 Dataset Information**

This project uses two datasets from TMDB:

tmdb_5000_movies.csv

tmdb_5000_credits.csv

They include:

Budget

Revenue

Genres

Cast / Crew

Popularity

Tagline, overview, runtime, etc.

**🎯 Goals of the Project**

Understand and analyze movie-related data

Build a predictive model using real-world features

Deploy the model using a simple web interface

Demonstrate workflow from EDA → ML → Deployment

**📈 Results of the Project**

Achieved good performance on validation set

Model saved and loaded for real-time predictions

Designed a user-friendly interface for prediction

(I can include graphs or metrics if you want.)
