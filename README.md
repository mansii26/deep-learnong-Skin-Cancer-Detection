# Skin Cancer Detection Project

This project aims to classify skin lesions using machine learning and deep learning techniques. It provides a user-friendly web interface for doctors and patients to upload skin images, predict results, and generate reports.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Workflow](#workflow)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Screenshots](#screenshots)
- [Future Work](#future-work)

---

## Overview
Skin cancer is one of the most common cancers globally. Early detection can significantly improve treatment outcomes. This project utilizes EfficientNet for image classification to distinguish between benign and malignant skin lesions. The system includes:
1. Data preprocessing pipeline.
2. EfficientNet model for training.
3. User interface to upload images and view predictions.

---

## Features
1. **Data Preprocessing**
   - Cleaning, cropping, and resizing images to standardized dimensions (768x768 and 512x512 pixels).
   - Imputation of missing demographic data using averages.

2. **Deep Learning Model**
   - Model training using EfficientNet.
   - Data augmentation for robust learning.
   - Validation accuracy tracking.

3. **User Interface**
   - Upload patient details and skin images.
   - View predictions with detailed graphs.
   - Generate PDF reports.

4. **Error Handling**
   - Verification of input formats for patient details and images.

---

## Workflow
### Data Processing Pipeline
1. Download dataset and labels for the years 2018, 2019, and 2020.
2. Clean and preprocess data:
   - Standardize dimensions.
   - Split into training and validation sets.
3. Train the EfficientNet model with hyperparameter tuning and data augmentation.
4. Save the trained model for predictions.

### Prediction Pipeline
1. Upload patient details and skin lesion images.
2. Process data through the trained model.
3. Display results with visualization graphs and downloadable PDF reports.

---

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript.
- **Backend**: Python, Flask/Django.
- **Deep Learning**: TensorFlow/Keras with EfficientNet.
- **Database**: SQLite/MySQL (for patient details).
- **Tools**: Docker, Git, Jupyter Notebook.
- **Visualization**: Matplotlib, Seaborn.

---

## How to Run
1. Clone the repository.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the backend server:
   ```bash
   python app.py
   ```
4. Open `localhost:5000` in your browser.

---

## Screenshots
### 1. Sample Skin Lesion Images
![Skin Lesion Images](https://github.com/mansii26/deep-learnong-Skin-Cancer-Detection/blob/main/readme_images/5.jpg)

### 2. Data Preprocessing Pipeline
![Data Pipeline](https://github.com/mansii26/deep-learnong-Skin-Cancer-Detection/blob/main/readme_images/6.jpg)

### 3. User Workflow
![User Workflow](https://github.com/mansii26/deep-learnong-Skin-Cancer-Detection/blob/main/readme_images/7.jpg)

---

## Future Work
1. Integrate more advanced models like Vision Transformers (ViT).
2. Expand dataset to include more diverse demographics.
3. Implement real-time predictions with a mobile app.
4. Add multi-language support to the user interface.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

For any questions or contributions, feel free to contact the project maintainer.

