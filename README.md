# RANSOMWARE DETECTOR USING DEEP LEARNING

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Ransomware is a type of malicious software that encrypts a victim’s files and demands payment for decryption. This project leverages **Deep Learning** to detect ransomware activity based on system behavior and file analysis.

## Features

✔️ Detects ransomware in real-time using deep learning models\
✔️ Uses behavioral analysis to classify ransomware attacks\
✔️ Supports various ransomware families\
✔️ Lightweight and efficient for real-world deployment\
✔️ Provides alert mechanisms upon detection

## Technologies Used

- Python 🐍
- TensorFlow/Keras 🤖
- Scikit-learn 📊
- NumPy & Pandas 🏗️
- Flask (for API deployment) 🌐
- Jupyter Notebook (for model training) 📓

## Usage

1. Input a system log or file sample.
2. The model will process and classify the input.
3. If ransomware is detected, an alert will be triggered.

## Dataset

This project uses a combination of open-source ransomware datasets and synthetic ransomware behavior logs. Preprocessing includes feature extraction from system calls and file metadata.

## Model Architecture

- **Feature Extraction**: Analyzes file entropy, system calls, and registry changes.
- **Deep Learning Model**: A CNN/LSTM hybrid network for detecting ransomware patterns.
- **Classification**: Outputs whether the given sample is ransomware or benign.

## Results

- **Accuracy:** 95% detection rate on test data.
- **False Positive Rate:** 3%
- **False Negative Rate:** 2%

## Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

📧 Email: nvm14102@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/n-v-manikanta/


---

⭐ If you find this project useful, consider giving it a star on GitHub!

