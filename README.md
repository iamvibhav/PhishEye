# PhishEye

PhishEye is a tool designed to detect phishing websites using machine learning techniques. This project aims to provide a robust solution for identifying and mitigating phishing threats by analyzing web page features.

## Dataset

The dataset used for training and testing the phishing detection model can be found on Kaggle: [Web Page Phishing Detection Dataset](https://www.kaggle.com/datasets/shashwatwork/web-page-phishing-detection-dataset)

## Features

- Machine learning-based detection of phishing websites
- Analysis of various features extracted from web pages
- High accuracy and low false-positive rate

![download](https://github.com/user-attachments/assets/9745f03b-9470-4778-88fb-21a63c33015a)
![table](https://github.com/user-attachments/assets/eda74078-072a-4d09-8507-40bd861be622)


## Installation

To install and set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/iamvibhav/PhishEye.git
    cd PhishEye
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use PhishEye, follow these instructions:

1. Prepare the dataset by downloading it from the provided link and placing it in the `data` directory.

2. Run the training script to train the model:
    ```bash
    python train.py
    ```

3. Use the trained model to detect phishing websites:
    ```bash
    python detect.py --url <URL_TO_CHECK>
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to the project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
