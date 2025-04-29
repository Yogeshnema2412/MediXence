# MediXence: AI-based Disease Prediction System

MediXence is a powerful AI-driven web application built using Flask that predicts potential diseases based on user-input symptoms. It provides detailed healthcare information, including disease descriptions, precautions, medications, recommended diets, and workout routines, to help users better understand and manage their health.

---

## ✨ Features

- **🔍 Disease Prediction**: Predict potential diseases based on selected symptoms.
- **📚 Disease Information**: Get detailed descriptions, precautions, medications, diet plans, and workout suggestions.
- **🖥️ User-Friendly Interface**: A clean and intuitive web application for smooth interaction.
- **📱 Responsive Design**: Fully optimized for desktop, tablet, and mobile devices.
- **🔒 Secure**: User privacy and data security are handled with care.

---

## 🛠️ Technologies Used

- **Flask**: Backend web framework.
- **HTML**: Webpage structure.
- **CSS (TailwindCSS)**: Responsive and modern UI design.
- **JavaScript**: Frontend interactivity.
- **Scikit-learn**: Machine learning for disease prediction (Support Vector Machine - SVM).
- **Pandas & NumPy**: Data processing and manipulation.
- **Pickle**: Saving and loading machine learning models.

---

## 🚀 File Structure



```bash


Personalized-Medical-Recommendation-System/
|
|
│
├── main.py               # Main Flask application file
├── datasets/            # Folder containing symptom and disease datasets
│   ├── symptoms.csv     # Symptoms data
│   ├── diseases.csv     # Disease data
│   └── medications.csv  # Medications data
│
├── models/              # Folder containing trained machine learning models
│   └── svc_model.pkl    # Trained Support Vector Machine model
│
├── templates/           # HTML templates for rendering web pages
│   ├── index.html       # Home page template
│   ├── about.html       # About page template
│   └── contact.html     # Contact page template
│
├── static/              # Folder for static files like CSS, JavaScript, and images
│   ├── css/             # CSS files (Tailwind)
│   └── js/              # JavaScript files
│
└── README.md            # Project documentation

```
## ⚙️ How It Works
- **Symptom Input**: Users select symptoms via a user-friendly form.

- **Disease Prediction**: The selected symptoms are processed and passed into a trained Support Vector Machine (SVM) model.

- **Results Display**:-

     - Predicted Disease Name

     - Detailed Disease Description

     - Precautionary Measures

     - Suggested Medications

     - Recommended Diet and Workout Plans

## 🌟 Future Enhancements
- **📱 Mobile App Integration**: Extend MediXence to Android and iOS platforms for easier access.

- **🎙️ Voice Input Support**: Enable users to input symptoms through voice commands.

- **🧠 Enhanced ML Models**: Incorporate deep learning models for even higher prediction accuracy.

- **🩺 Real-time API Integration**: Connect with live health databases for updated recommendations.

## 📬 Contact
**Email*: contact@medixence.com

**GitHub*: https://github.com/Yogeshnema2412/MediXence

## 📷 Demo


![Screenshot 2025-04-28 233600](https://github.com/user-attachments/assets/61efb2fe-81f7-44ac-b43f-9d917e683583)


