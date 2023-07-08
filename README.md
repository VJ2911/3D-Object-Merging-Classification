# 3D-objects-merging-classification
An approach to classify whether a object is Merged in 3d space or not.

This repository contains the code and dataset for the "3D Objects Merging Classification" project. The project aims to classify whether an object is merged or not in a 3D space. It utilizes a self-designed dataset consisting of SketchUp (.obj) files, combined with self-labeled data stored in CSV files. The purpose of this project is to demonstrate an approach for classifying merged objects using machine learning techniques.

Dataset Overview
The dataset used in this project consists of SketchUp (.obj) files representing various 3D objects. Each object is labeled as either "merged" or "not merged" and the corresponding labels are stored in CSV files. The dataset provides a diverse range of objects and their merging status to train and evaluate the classification model.

Approach
The classification approach employed in this project involves the following steps:

Data Preparation: The SketchUp (.obj) files are processed and converted into a suitable format for training the classification model. The necessary preprocessing steps are implemented to extract relevant features from the 3D objects.

Feature Extraction: The extracted features are used to represent each object. These features capture important characteristics related to merging status, such as surface area, volume, and geometric properties of the objects.

Model Training: A machine learning model is trained using the labeled dataset to classify objects as "merged" or "not merged." Various classification algorithms can be explored, such as support vector machines (SVM), random forests, or neural networks, to find the most suitable model for the task.

Model Evaluation: The trained model is evaluated using appropriate evaluation metrics, such as accuracy, precision, recall, and F1 score, to assess its performance and generalization capabilities. Cross-validation techniques can be applied to ensure robustness.

Contact
If you have any questions or feedback regarding this project, please feel free to contact the project maintainers:

Varun Jain
