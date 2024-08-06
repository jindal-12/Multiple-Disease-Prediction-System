# Multiple Disease Prediction System

## Overview

The Multiple Disease Prediction System is a machine learning-based application designed to predict the likelihood of multiple diseases based on user input data. The system leverages various algorithms to provide accurate predictions, enabling early detection and preventive measures for a range of diseases.

## Features

- Predicts multiple diseases based on user input.
- Utilizes machine learning algorithms for accurate predictions.
- User-friendly interface for easy data input.
- Provides detailed results and recommendations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

### Prerequisites

- Python 3.7 or above
- pip (Python package installer)

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/multiple-disease-prediction-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd multiple-disease-prediction-system
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:

    ```bash
    python app.py
    ```

2. Open your web browser and go to:

    ```
    http://127.0.0.1:5000/
    ```

3. Input the required data for prediction and submit.

4. View the prediction results and recommendations.

![Home Page Screenshot](screenshots/Screenshot.png)

## Technologies

- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - Bootstrap

- **Backend:**
  - Flask

- **Machine Learning:**
  - Scikit-learn
  - Pandas
  - NumPy

## Model Training

The system uses various machine learning algorithms to train models for different diseases. The training data includes various health indicators and patient records.

### Steps for Model Training

1. Prepare the dataset.
2. Preprocess the data (handling missing values, encoding categorical variables, etc.).
3. Split the dataset into training and testing sets.
4. Train the models using algorithms like Logistic Regression, Random Forest, etc.
5. Evaluate the models using metrics such as accuracy, precision, recall, and F1-score.
6. Save the trained models for prediction.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to all contributors and the open-source community.
- Special thanks to the developers and researchers who created the machine learning algorithms and libraries used in this project.
