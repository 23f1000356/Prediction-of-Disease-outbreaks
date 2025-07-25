# Disease Outbreak Prediction System

A machine learning-powered web application built with Streamlit that predicts the likelihood of three major diseases: Diabetes, Heart Disease, and Parkinson's Disease. This system uses pre-trained machine learning models to provide quick and accurate health assessments based on user input.
    
## 🚀 Features

- **Multi-Disease Prediction**: Supports prediction for three critical health conditions
- **Interactive Web Interface**: User-friendly Streamlit-based GUI
- **Real-time Results**: Instant predictions based on input parameters
- **Input Validation**: Comprehensive error handling for invalid inputs
- **Responsive Design**: Works seamlessly across different devices

## 🏥 Supported Disease Predictions

### 1. Diabetes Prediction
Predicts diabetes risk based on:
- Number of pregnancies
- Glucose level
- Blood pressure
- Skin thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes pedigree function
- Age

### 2. Heart Disease Prediction
Assesses heart disease risk using:
- Age and gender
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia

### 3. Parkinson's Disease Prediction
Evaluates Parkinson's disease likelihood through voice analysis parameters:
- MDVP fundamental frequency measures
- Jitter and shimmer measurements
- Noise-to-harmonics ratio (NHR)
- Harmonics-to-noise ratio (HNR)
- Recurrence period density entropy (RPDE)
- Detrended fluctuation analysis (DFA)
- Spread and correlation measures
- Pitch period entropy (PPE)

## 🛠️ Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Prediction-of-Disease-outbreaks.git
   cd Prediction-of-Disease-outbreaks
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run app.py.py
   ```

4. **Access the application**
   Open your web browser and navigate to `http://localhost:8501`

## 📦 Dependencies

- **streamlit**: Web application framework
- **streamlit-option-menu**: Enhanced sidebar menu component
- **scikit-learn**: Machine learning library
- **numpy**: Numerical computing library
- **pickle**: Model serialization (built-in Python module)

## 🏗️ Project Structure

```
Prediction-of-Disease-outbreaks/
│
├── app.py.py                 # Main Streamlit application
├── requirements.txt          # Python dependencies
├── README.md                # Project documentation
├── jasonfile.json           # Development container configuration
│
├── Saved_Models/            # Pre-trained ML models
│   ├── diabetes.sav
│   ├── heartdisease.sav
│   └── parkinsons.sav
│
├── Datasets/                # Training datasets (if available)
│
└── Models/                  # Model training notebooks
    ├── diabetes.ipynb
    └── heartdisease.ipynb
```

## 🔬 Model Information

The application uses pre-trained machine learning models saved in pickle format:

- **Diabetes Model**: Trained on the Pima Indians Diabetes Database
- **Heart Disease Model**: Based on the Cleveland Heart Disease dataset
- **Parkinson's Model**: Trained on voice measurement data from Parkinson's patients

## 💻 Usage

1. **Launch the application** using the installation instructions above
2. **Select a prediction type** from the sidebar menu
3. **Enter the required parameters** in the input fields
4. **Click the prediction button** to get results
5. **View the diagnosis** displayed on the screen

### Input Guidelines

- All numerical values must be entered as numbers (integers or decimals)
- Binary inputs (like gender) should be entered as 0 or 1
- Ensure all fields are filled before clicking the prediction button
- The system will display error messages for invalid inputs

## 🎯 Accuracy and Limitations

- **Educational Purpose**: This tool is designed for educational and research purposes
- **Not a Medical Diagnosis**: Results should not replace professional medical consultation
- **Model Limitations**: Predictions are based on training data and may not account for all medical factors
- **Consult Healthcare Professionals**: Always seek professional medical advice for health concerns

## 🚀 Development Environment

This project includes a development container configuration (`jasonfile.json`) for:
- **GitHub Codespaces** support
- **VS Code Dev Containers** compatibility
- **Automatic dependency installation**
- **Pre-configured Python environment**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you encounter any issues or have questions:
- Create an issue in the GitHub repository
- Check the existing documentation
- Review the requirements and installation steps

## 🔮 Future Enhancements

- [ ] Add more disease prediction models
- [ ] Implement model retraining capabilities
- [ ] Add data visualization for predictions
- [ ] Include confidence scores for predictions
- [ ] Add user authentication and history tracking
- [ ] Implement API endpoints for external integration

## ⚠️ Disclaimer

This application is for educational and informational purposes only. It is not intended to be a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

---

**Built with ❤️ using Streamlit and Machine Learning**
