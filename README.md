# Smartphone Price Predictor

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![AWS SageMaker](https://img.shields.io/badge/AWS%20SageMaker-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

This project builds a **smartphone price range classifier** that predicts whether a phone falls into the Budget, Lower Mid-Range, Upper Mid-Range or Premium category based on its hardware specifications.
The model is trained using a **Random Forest Classifier** with scikit-learn on a dataset of 20 smartphone features, including RAM, battery, camera resolution, screen size and connectivity options.
The trained model is deployed as an **AWS SageMaker endpoint**, exposing real-time inference via a Python Flask web application that handles user input and returns predictions.
Users interact through a clean & responsive HTML/CSS/JS interface that accepts all 20 specifications and displays the predicted price range instantly.
This end-to-end project demonstrates practical skills across data preprocessing, ML model training, cloud-based model deployment and full-stack web integration.

---

## Features

- Predicts smartphone price range in 4 categories:
  - Budget mobile phone
  - Lower mid-range phone
  - Upper mid-range phone
  - Premium phone
- Interactive web interface with real-time predictions
- Responsive design that works on desktop and mobile devices
- Handles 20 different smartphone specifications for prediction.

---

## Tech Stack

- **Frontend**: HTML, CSS & JS.
- **Backend**: [Flask](https://flask.palletsprojects.com/en/2.2.x/) (Python)
- **ML Model Deployment**: [AWS SageMaker](https://aws.amazon.com/sagemaker/)
- **AWS Services**: AWS Sagemaker, AWS S3, AWS IAM and AWS CLI.

---

## Prerequisites

- Python 3.x
- [AWS Account](https://aws.amazon.com/) with appropriate credentials
- [Boto3 library](https://boto3.amazonaws.com/)
- [Flask](https://flask.palletsprojects.com/en/2.2.x/)

---

## Installation

1. Clone the repository
```bash
https://github.com/AdarshZolekar/Smartphone-Price-Predictor.git
```

2. Install required packages
```bash
pip install flask boto3
```

3. Configure AWS credentials
```bash
aws configure
AWS_ACCESS_KEY_ID='your-access-key'
AWS_SECRET_ACCESS_KEY='your-secret-key'
AWS_REGION='ap-south-1'
```

---

## Usage

1. Start the Flask application:
```bash
python App.py
```

2. Open a web browser and navigate to `http://localhost:5000`

3. Enter the smartphone specifications in the form:
   - Basic specifications (RAM, storage, processor, etc.)
   - Camera details
   - Screen specifications
   - Additional features (Bluetooth, WiFi, etc.).

4. Click "Predict Price Range" to get the prediction.

---

## Screenshots

![Smartphone Price Predictor Interface](https://github.com/AdarshZolekar/Smartphone-Price-Predictor/blob/main/Screenshot.png)
*Smartphone Price Predictor Web Interface*

---

## License

This project is open-source under the MIT License.

---

## Contributions

Contributions are welcome!

- Open an issue for bugs or feature requests

- Submit a pull request for improvements.


<p align="center">
  <a href="#top">
    <img src="https://img.shields.io/badge/%E2%AC%86-Back%20to%20Top-blue?style=for-the-badge" alt="Back to Top"/>
  </a>
</p>




