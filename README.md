# Symptom-Checker-app
![Screenshot 2025-03-09 191550](https://github.com/user-attachments/assets/225fce6e-11cb-4e46-b06c-f3d5bcf8f031)


---

# **Disease Prediction App 🩺**

The **Disease Prediction App** is a machine learning-based web application designed to predict potential diseases based on selected symptoms. Using a trained model, it provides a user-friendly interface for individuals to input their symptoms and get predictions instantly.

---

## **Features**

- **Symptom Selection**: Users can choose from a list of symptoms to indicate what they are experiencing.
- **Disease Prediction**: The app uses a machine learning model to predict the most likely disease.
- **Interactive Interface**: Built with **Gradio**, it offers an intuitive and modern interface.
- **Fast and Accurate**: Provides predictions in real-time based on a pre-trained model.

---

## **How It Works**

1. **Input Symptoms**: Select the symptoms that best describe what you are experiencing.
2. **Model Prediction**: The app processes the input through a trained ML model.
3. **Get Results**: The predicted disease is displayed instantly.

> **Note**: This tool is for educational purposes and should not replace professional medical advice.

---

## **Technologies Used**

- **Python**: Backend programming language.
- **Gradio**: For building the web interface.
- **Pandas**: For data processing.
- **Joblib**: For loading the trained machine learning model.
- **Scikit-learn**: For training the machine learning model (logistic regression).

---

## **Setup Instructions**

### **To Run Locally**

1. Clone the repository:
   ```bash
   git clone https://github.com/HassanCodesIt/disease-prediction-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd disease-prediction-app
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open the app in your browser at `http://127.0.0.1:7860`.

---

## **Demo**

You can try the live app hosted on [Vercel](https://vercel.app/) (or any other hosting platform, insert the link here).

---

## **Project Files**

- **`app.py`**: The main Python script for the Gradio app.
- **`disease_prediction_model.pkl`**: The pre-trained machine learning model.
- **`requirements.txt`**: List of dependencies for the project.
- **`README.md`**: Documentation and instructions for the repository.

---

## **Deployment**

This app can be deployed on platforms like:

- **[Vercel](https://vercel.com/)**
- **[Render](https://render.com/)**
- **[Heroku](https://www.heroku.com/)**

---

## **Future Enhancements**

- Add more symptoms to the database for improved predictions.
- Integrate with a medical database for verified results.
- Provide recommendations for follow-up actions or medical advice.

---

## **Contributing**

Contributions are welcome! If you want to contribute:

1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes.
4. Open a pull request.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

