🚦 Traffic Prediction System using Machine Learning
📌 Overview
The Traffic Prediction System is a machine-learning–based project that predicts traffic conditions using historical traffic data.
It aims to help in traffic congestion analysis, forecasting, and smart transportation planning.

This project focuses on:

Data preprocessing and feature engineering
Training and evaluating multiple ML models
Comparing model performance
Predicting traffic conditions efficiently
🎯 Objectives
Predict traffic congestion levels accurately
Analyze historical traffic patterns
Compare different machine learning models
Build a scalable and reusable ML pipeline
🧠 Machine Learning Models Used
The following models are implemented and evaluated:

Random Forest Classifier
Extra Trees Classifier
Best Classifier Model (selected based on performance metrics)
⚠️ Note:
Trained model files (.pkl) are not stored in this repository due to GitHub file-size limitations.

🗂️ Project Structure
Traffic-Prediction-System/ │ ├── data/ │ └── traffic_data.csv │ ├── notebooks/ │ └── exploratory_analysis.ipynb │ ├── src/ │ ├── data_preprocessing.py │ ├── feature_engineering.py │ ├── train_model.py │ ├── evaluate_model.py │ └── predict.py │ ├── requirements.txt ├── .gitignore └── README.md

⚙️ Technologies Used
Programming Language
Python 3.x
Libraries & Frameworks
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
XGBoost (optional)
📊 Dataset
The dataset contains historical traffic data such as:

Vehicle count
Date and time features
Road conditions
Weather attributes (if available)
📌 Large datasets are not included in the repository.
Place them locally inside the data/ directory.

🧪 Model Training
To train the models locally:

python src/train_model.py
This will:

Preprocess the dataset

Train multiple ML models

Save trained models locally (.pkl)

🔍 Model Evaluation
To evaluate the trained models:

python src/evaluate_model.py
Evaluation metrics include:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

🚀 Traffic Prediction
To predict traffic conditions on new data:

python src/predict.py
📁 Trained Models (Important)
Due to GitHub’s file-size restrictions, trained model files (.pkl) are excluded.

Options to obtain models:
Train models locally using train_model.py

Download pre-trained models from an external source (Google Drive / HuggingFace)

Example:

https://drive.google.com/your-model-link
📦 Installation & Setup
Step 1: Clone the repository
git clone https://github.com/Moksha2005-web/Traffic-Prediction-System.git
cd Traffic-Prediction-System
Step 2: Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
Step 3: Install dependencies
pip install -r requirements.txt
🛑 Excluded from Repository
The following files are intentionally excluded:

Virtual environments (venv/)

Trained ML models (.pkl)

Large binary files (.dll, datasets)

This follows industry-standard Git and ML practices.

🧠 Future Enhancements
Real-time traffic prediction using APIs

Deep learning models (LSTM, GRU)

Web dashboard integration

Deployment using Flask / FastAPI

Cloud-based model hosting

👨‍💻 Author
Moksha Pawan Kumar
B.Tech Student | Machine Learning Enthusiast

📜 License
This project is intended for educational and academic use.
You are free to fork, modify, and enhance it with proper attribution.

⭐ Acknowledgements
Scikit-learn Documentation

Open Traffic Datasets

Research papers on traffic flow prediction