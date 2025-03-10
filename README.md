# Machine Learning Classifier for Sorting Lego Pieces

## Description
This project focuses on developing and training a machine learning model for image-based classification of Lego pieces. The system utilizes Python and Logistic Regression to classify 
Lego pieces based on their shape and engineered features

## Project Status
- **Stage 1**: Completed.
- **Stage 2**: Completed.

## Key Features
Stage 1: Sorting Using Raw Images
- Developed a machine learning model in Python for Lego shape classification (rectangles, squares, circles) using raw RGB images.
- Implemented preprocessing techniques including **grayscale conversion** and **cropping** to optimize a 4-class classification model.
- Achieved **97.2% accuracy** on test data, demonstrating strong generalization capabilities.
- Used a confusion matrix to evaluate performance on both training and testing datasets.

Stage 2: Sorting Using Engineered Features
- Addressed challenges posed by varied Lego piece orientations and off-centered objects.
- Designed 11 engineered features to enhance sorting precision and robustness.
- Achieved 90.0% accuracy on the test dataset.
- Compared the performance of the raw-image-based classifier (Stage 1) and the feature-based classifier (Stage 2).

## Authors
- **Amer Alhamwi**  
- **Wael Hamid**  
- Date: Febuary 18th, 2025  

## Repository Structure
- **Project_Stage_1/**: Contains code and data for Stage 1 development.
- **Project_Stage_2/**: Contains code and data for Stage 2 development.
- **README.md**: Project overview.

## Usage
# Clone the repository
git clone https://github.com/your-username/Lego-Classification-Project.git
# Navigate to the project folder
cd Lego-Classification-Project
# Navigate to Stage 1 or Stage 2
cd Project_Stage_1  # or cd Project_Stage_2
# Run the script
