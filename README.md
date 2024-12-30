# PhishNet: Phishing URL Detection System

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Framework-red?style=for-the-badge&logo=streamlit&logoColor=white)
![RandomForest](https://img.shields.io/badge/Model-Random_Forest-green?style=for-the-badge)


## Project Description
PhishNet is a web-based application that predicts whether a given URL is safe or a phishing attack. Built using the **Streamlit** framework, the application leverages a pre-trained **Random Forest** model to provide accurate predictions.

## Features
- **Input URL**: Enter a URL to analyze its safety.
- **Prediction**: Provides a result indicating whether the URL is safe or phishing.
- **Interactive UI**: Built with Streamlit for a user-friendly experience.

## Technologies Used
- **Python**: Core programming language.
- **Streamlit**: For building the web interface.
- **Random Forest Model**: Machine learning algorithm used for predictions.
- **Pandas & Scikit-Learn**: For data processing and model development.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YashSakhareliya/PhishNet-Phishing-URL-Detection-System.git
   cd PhishNet-Phishing-URL-Detection-System
   ```

2. **Install Dependencies:**
   Ensure you have Python 3.8+ installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

4. **Access the Application:**
   Open your browser and go to `http://localhost:8501`.

## Usage
1. Open the application.
2. Enter a URL into the input field.
3. Click the "Predict" button.
4. View the result indicating whether the URL is safe or phishing.

## Model Information
- The **Random Forest Model** was trained on a dataset of labeled URLs with features extracted for safety analysis.
- Training achieved high accuracy and reliability.

## Screenshots
Coming Soon...

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit.
4. Push to your branch and create a pull request.

## License
This project is licensed under the MIT License.

---

**Made with ❤ by Yash Sakhareliya.**
