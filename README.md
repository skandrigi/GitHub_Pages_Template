# Lung and Colon Cancer Classification

*Implemented machine learning algorithms to differentiate between cancerous and benign lung cells, enhancing early diagnosis of lung cancer. Leveraged skills in ML, data analysis, and computational biology within AI4ALL's Ignite program, showcasing AI's impactful role in healthcare.*


## Problem Statement <!--- do not change this line -->

*The motivation behind the project of using machine learning and tools to distinguish between cancerous and benign cells in human lungs stems from the urgent need to improve early detection and diagnosis of lung cancer. Lung cancer remains one of the leading causes of cancer-related deaths worldwide, with a high mortality rate often attributed to late-stage diagnoses.*

## Key Results <!--- do not change this line -->
The model can be retrieved at ebmonser/lung-cancer-image-classification on huggingface
The model acheives the following results on the testing set:
Loss: 0.0177
Precision: 0.9963
Recall: 0.9963
F1: 0.9963
Accuracy: 0.9963
Confusion matrix: 1245 1 4 0 1250 0 9 0 1241

## Methodologies <!--- do not change this line -->

We started the project by utilizing the Kaggle API within a Python environment in Google Colab to procure lung histopathological images from Kaggle. Then, we employed pandas for data preprocessing and organization, ensuring uniformity across the dataset.

For model training, we fine-tuned a Vision Transformer (ViT) model using PyTorch, a powerful deep learning framework. Throughout the training process, we leveraged NumPy for efficient numerical computations and utilized Matplotlib for advanced visualization of training progress.

Following model training, we evaluated the model's performance on a separate testing dataset using scikit-learn for computing key evaluation metrics such as precision, recall, F1 score, and accuracy. Additionally, we utilized Matplotlib for generating a confusion matrix, providing deeper insights into the model's classification performance.

Finally, we visualized the evaluation results using Matplotlib, enabling clear interpretation of the model's performance. This systematic approach, integrating various technologies and leveraging TensorBoard for monitoring, facilitated the development and assessment of a robust image classification model for lung histopathological images.

## Data Sources <!--- do not change this line -->

*Lung and Colon Cancer Histopathological Images: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images/code*

## Technologies Used <!--- do not change this line -->

- *Python*
- *pandas*
- *scikit-learn*
- *Matplotlib*
- *PyTorch*
- *NumPy*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Gabriel Wild ([gabew2024@tamu.edu](mailto:gabew2024@tamu.edu))*
- *Elizabeth Monser ([emonser@terpmail.umd.edu](mailto:emonser@terpmail.umd.edu))*
- *Sandeep Kandrigi ([skandrigi1@tamu.edu](mailto:skandrigi1@tamu.edu))*
