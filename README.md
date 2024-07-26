# Paddle vs Tennis Classification Project


<div align="center">
  <img src="https://github.com/user-attachments/assets/596195ef-cc62-4f76-a22d-ab4018701a60" width="25%" height="25%">
</div>

## Overview

Welcome to the Paddle vs Tennis Classification Project! This project focuses on developing a machine learning model to distinguish between features (acceleration) of paddle and tennis sports. By leveraging advanced classification techniques, our goal is to accurately classify images into either the paddle or tennis category. This project is ideal for demonstrating skills in machine learning.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)

## Project Description

This project uses machine learning algorithms to classify images of paddle and tennis. We apply feature extraction, and classification methods to achieve high accuracy. The end result is a robust classifier that can differentiate between the two sports based on acceleration data.

## Features

- **Feature Extraction:** Utilization of advanced features for better classification accuracy.
- **Machine Learning Models:** Implementation of various parameters and techniques to find the best Support Vector Machines (SVM) classifier.
- **Evaluation Metrics:** Comprehensive evaluation of model performance using metrics like accuracy, F1-score, and confusion matrix.
- **Visualization:** Graphical representation of results including decision boundaries and confusion matrices.

## Installation

To get started with this project, follow the instructions below to set up your environment:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/luisgrana2/paddletenisAI.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd paddletenisAI
    ```

3. **Install required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the classifier, follow these steps:

1. **Prepare your dataset:** Ensure that your images are organized into 'pl' and 'tl' directories within the `data` folder. [DataSet](https://www.dropbox.com/scl/fo/lavmrileb4d7olcy0jh90/ABZszViGbK9945CHZthSJq8?rlkey=jx2k6er74xwxykyeo5pwlmpys&st=5a2c42mp&dl=0)
2. **Run the training script, evalute the model and classify:**

    ```bash
    python source.ipynb
    ```

## Data

The dataset for this project consists of accelerations in the 3 different axis for paddle and tennis. The data is organized into two directories: `data/pl` and `data/tl`. Ensure your dataset follows this structure for the code to work correctly.

The data for this project was obtained using the MATLAB mobile application, that use phone sensors to record the accelerations. The creators of the code played real matches to collect this data, ensuring its authenticity and relevance for training and testing the classification models.

## Model Training

We used various machine learning models for classification, including:

- **SVM** were chosen for this project due to their high precision and effectiveness with the volume of data obtained. Given the nature of our data and the need for accurate classification, SVMs provide robust performance and reliable results.

The best-performing model was selected based on cross-validation and evaluation metrics.

## Evaluation

Model performance was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

These metrics provide a comprehensive understanding of the classifier's performance.

## Results

The project results indicate the accuracy and effectiveness of the classifier in distinguishing between paddle and tennis images. Visualizations include confusion matrices and decision boundaries that illustrate the model's performance.

<div align = "center">


| Class      | Precision | Recall | F1-Score | Support |
|------------|-----------|--------|----------|---------|
| P          | 0.80      | 0.89   | 0.84     | 9       |
| T          | 0.86      | 0.75   | 0.80     | 8       |
| **Accuracy**  |           |        | 0.82     | 17      |
| **Macro Avg** | 0.83      | 0.82   | 0.82     | 17      |
| **Weighted Avg** | 0.83  | 0.82   | 0.82     | 17      |
</div>

## Contributing

We welcome contributions to improve this project! Please fork the repository and submit pull requests with your enhancements or bug fixes. For major changes, please open an issue to discuss what you would like to change.

## Contact

For any questions or inquiries, please contact:

- **Luis Granados** - [lgsgranados@gmail.com](mailto:lgsgranados@gmail.com)
- **GitHub Profile** - [luisgrana2](https://github.com/luisgrana2)
- **LinkedIn Profile** - [Luis Granados](https://www.linkedin.com/in/luis-granados-segura-099290222/)
