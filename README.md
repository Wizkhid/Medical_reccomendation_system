💊 Medical Recommendation System

A machine learning web app built with **Streamlit** that predicts diseases based on user-selected symptoms and provides recommendations including precautions, medications, diets, and workouts.

🚀 Features

- User-friendly Streamlit interface
- Predicts disease based on selected symptoms
- Provides detailed medical recommendations:
  - Disease description
  - Precautions
  - Medications
  - Diet recommendations
  - Workouts
- Deployable on Streamlit Community Cloud

📂 Project Structure

Medical_reccomendation_system/
├── app2.py                     # Main Streamlit app
├── Model/
│   └── svc.pkl                 # Pre-trained SVC model
├── Dataset/
│   ├── symtoms_df.csv          
│   ├── precautions_df.csv      
│   ├── workout_df.csv          
│   ├── description.csv         
│   ├── medications.csv         
│   └── diets.csv               
├── requirements.txt            # Dependencies
├── Medical Recommendation.ipynb # Notebook for experimentation
└── README.md                   # Project documentation

🌍 Deployment

The app can be deployed on **Streamlit Community Cloud**.

📊 Model Details

- Algorithm: Support Vector Classifier (SVC)  
- Libraries: scikit-learn, pandas, numpy, pickle  
- Dataset: Symptom-disease mapping CSVs

🛠️ Requirements

See `requirements.txt` for dependencies.

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss your ideas.

⚠️ Notes

This app is for **educational purposes only** and does not replace professional medical advice.


👨🏽‍💻 Author

**AbdulHameed Idris**  
- GitHub:https://github.com/wizkhid
- LinkedIn:www.linkedin.com/in/airways22
