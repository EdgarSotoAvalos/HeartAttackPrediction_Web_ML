# Heart Disease Prediction Web App

This project is a web application that utilizes a trained Machine Learning model to predict the risk of heart diseases based on input features. It uses Flask as the web framework and a Naive Bayes classifier as the Machine Learning model.

## Requirements

Before running the web app, make sure you have the following installed:

- Python (>= 3.6)
- Flask (>= 1.1.2)
- NumPy (>= 1.19.5)
- scikit-learn (>= 0.24.2)

You can install the required dependencies using `pip` with the following command:
```bash
pip install Flask numpy scikit-learn
```

## Getting Started

1. Clone this repository to your local machine.

2. Make sure you have the dataset `heart.csv` in the same directory as the Jupyter Notebook `notebook.ipynb`.

3. Run the Jupyter Notebook `notebook.ipynb` to preprocess the dataset and train the Naive Bayes classifier. The trained model will be saved as `model.pkl`.

4. Once the model is trained, you can run the Flask web app using the following command:
```bash
python app.py
```

5. Open your web browser and go to `http://127.0.0.1:5000/` to access the web app.

## How to Use

The web app provides a simple user interface to enter the following input features:

- Age
- Sex (1 for male, 0 for female)
- Chest Pain Type
- Resting Blood Pressure (in mm Hg)
- Cholesterol (in mg/dl fetched via BMI sensor)
- Fasting Blood Sugar (1 for true, 0 for false)
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina (1 for yes, 0 for no)
- Previous peak
- Slope
- Number of Major Vessels (0-3)
- Thal rate

After entering the required information, click the "Predict Heart Attack Risk" button to obtain the predicted result.

**Important Note:** This prediction model is accurate, but it does not replace the diagnosis and advice of a qualified medical professional. If you have concerns about your cardiac health, we strongly recommend seeking the advice of a physician.

## Dataset

The dataset used to train the model can be found at [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset). It is a diverse and comprehensive dataset used to predict the risk of heart diseases.

## Disclaimer

This project is for educational and demonstration purposes only. The creators and contributors of this project are not responsible for any misuse or reliance on the predictions made by the model. Always consult a qualified medical professional for any health-related concerns.

## Authors

- [Edgar Soto Avalos](https://github.com/EdgarSotoAvalos)

## License

This project is licensed under the [MIT License](LICENSE).

---




