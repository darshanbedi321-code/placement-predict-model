🎓 Placement Prediction System


An end-to-end Machine Learning web application that predicts a student's placement probability based on academic performance (CGPA) and aptitude (IQ Score). The application leverages a trained Logistic Regression model and provides instant predictions through an interactive Streamlit interface.


🚀 Features
Predicts student placement outcomes in real time.
Displays placement probability as a confidence score.
Clean and intuitive Streamlit-based user interface.
Machine Learning model deployment using Pickle.
Fast and lightweight prediction system.
User-friendly input validation for IQ and CGPA values.
🧠 Machine Learning Model
Algorithm: Logistic Regression
Input Features: IQ Score, CGPA
Output: Placed / Not Placed
Model Accuracy: ~90%
Framework: Scikit-learn
🛠️ Tech Stack
Python
Scikit-learn
Streamlit
NumPy
Pandas
Pickle
📂 Project Structure
Bash
Placement-Prediction-System/
│
├── app.py                 # Streamlit web application
├── model.pkl              # Trained ML model
├── requirements.txt       # Project dependencies
├── dataset.csv            # Training dataset
└── README.md              # Project documentation
⚡ Installation
Clone the repository:
Bash
git clone https://github.com/darshanbedi321/Placement-Prediction-System.git
cd Placement-Prediction-System
Install dependencies:
Bash
pip install -r requirements.txt
Run the application:
Bash
streamlit run app.py
📊 How It Works
Enter the student's IQ Score.
Enter the student's CGPA.
Click Check Placement.
The model predicts whether the student is likely to be placed.
Placement probability is displayed as a confidence percentage.
🎯 Future Improvements
Support additional features such as communication skills, internships, and technical assessments.
Compare multiple machine learning algorithms.
Deploy the application on Streamlit Cloud.
Add model explainability using SHAP.
Store prediction history and analytics.
📸 Demo
Add screenshots of the application here after deployment.
🤝 Contributing
Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.
📜 License
This project is open-source and available under the MIT License
