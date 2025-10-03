#📌 Resume Job Recommendation System

This project is a Resume Job Recommendation System built using Python, Flask, Machine Learning, HTML, CSS, and Kaggle datasets. It categorizes resumes, extracts key information, and recommends suitable jobs using trained ML models.

🚀 Features

Resume categorization using trained ML models

Job recommendation system based on extracted resume features

Flask web application with HTML & CSS frontend

Preprocessed datasets from Kaggle

Modular structure with separate folders for datasets, models, templates, and backend

📂 Project Structure
├── datasets/                     # Kaggle datasets (resumes, jobs, features)
├── models/                       # Trained ML models (pickle files)
├── templates/                    # HTML files for Flask frontend
├── venv/                         # Virtual environment (not included in GitHub)
├── app.py                        # Flask application entry point
├── clean_resume_data.xlsx        # Preprocessed resume dataset
├── jobs_dataset_with_features.xlsx # Jobs dataset with extracted features
├── Resume_Categorization.ipynb   # Notebook for training resume categorization model
├── Resume Job Recommendation System.ipynb # Notebook for recommendation engine
├── Extracted info and hiring process.ipynb # Notebook for preprocessing & feature extraction
└── README.md                     # Project documentation
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/resume-job-recommendation-system.git
cd resume-job-recommendation-system

2️⃣ Create virtual environment
python -m venv venv
3️⃣ Activate virtual environment
On Windows
venv\Scripts\activate
On Linux/Mac:
source venv/bin/activate
4️⃣ Install dependencies
pip install -r requirements.txt
▶️ Usage
1️⃣ Run Flask app

python app.py
2️⃣ Open in browser

Go to:
http://127.0.0.1:5000/
3️⃣ Upload Resume

Upload a resume in text/PDF format

The system will categorize it (e.g., Data Science, Web Development, etc.)

It will recommend suitable jobs from the dataset

📊 Datasets

We used Kaggle datasets for resumes and job postings:

Kaggle Resume Dataset

🧠 Machine Learning Models

The ML models are stored in the models/ folder:

Resume Categorization Model (rf_classifier_categorization.pkl)

TF-IDF Vectorizer (tfidf_vectorizer_categorization.pkl)

Job Recommendation Model (content-based filtering)

🌐 Technologies Used

Backend: Python, Flask

Frontend: HTML, CSS, Bootstrap

Machine Learning: Scikit-learn, Pandas, Numpy

Data: Kaggle Datasets

Deployment Ready: Can be deployed on Heroku / Render / AWS

📌 Future Improvements

Add NLP-based deep learning model (BERT/Transformers)

Improve job recommendations with hybrid (content + collaborative) filtering

Deploy as a full-stack application with user login

👨‍💻 Contributors

Naman Sharan Yadav
