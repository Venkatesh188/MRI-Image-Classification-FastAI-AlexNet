# MRI Image Classification Using FastAI and AlexNet

## Overview
This project is aimed at classifying MRI images into different categories using the FastAI library and a pretrained AlexNet model. MRI scans are essential in medical diagnostics, and automating the classification process can significantly aid in quicker and more accurate diagnoses.

## Project Structure
- **data/**: Contains the MRI images dataset (not included in the repository; refer to the instructions below on how to obtain the data).
- **notebooks/**: Jupyter notebooks for data preprocessing, model training, and evaluation.
  - `MRI_Image_Classification_AlexNet.ipynb`: Main notebook that includes all steps from data loading, preprocessing, model training, and evaluation.
- **models/**: Directory where the trained model weights will be saved (optional).

## Dataset
The dataset used for this project consists of MRI images, categorized by specific brain conditions. Due to medical data privacy, the dataset is not included in this repository. You can obtain a similar dataset from open sources like [Kaggle](https://www.kaggle.com/) or other medical imaging repositories.

## How to Run the Project
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/MRI-Image-Classification-FastAI-AlexNet.git
    cd MRI-Image-Classification-FastAI-AlexNet
    ```

2. **Set up the environment**:
    - Install the required dependencies using `pip`:
      ```bash
      pip install -r requirements.txt
      ```
    - Ensure that you have a compatible GPU if you want to speed up the training process.

3. **Prepare the data**:
    - Download the dataset and place it in the `data/` directory.
    - Update the dataset path in the notebook accordingly.

4. **Run the Jupyter notebook**:
    - Open `MRI_Image_Classification_AlexNet.ipynb` in Jupyter Notebook or JupyterLab.
    - Follow the steps outlined in the notebook to preprocess the data, train the model, and evaluate its performance.

5. **Model Evaluation**:
    - The notebook includes detailed evaluation metrics, including accuracy, confusion matrix, and more to assess the model's performance.

## Results
- The AlexNet model achieved a significant accuracy in classifying MRI images, demonstrating its potential for use in real-world medical applications.
- The model's performance can be further improved by fine-tuning, using a more complex model, or augmenting the dataset.

## Future Work
- Experiment with other architectures like ResNet or EfficientNet.
- Explore transfer learning techniques using more advanced models.
- Apply data augmentation techniques to improve model robustness.

## Acknowledgments
- The FastAI library for making deep learning accessible.
- The creators of the MRI dataset for providing the data used in this project.
