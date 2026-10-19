# Grad-CAM-Integrated-CNN-for-Explainable-Brain-Tumor-Classification-and-Localization
Explainable deep learning framework for brain tumor classification and localization using CNN and Grad-CAM on MRI images, achieving 97% test accuracy.
## Technologies Used

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Model Architecture:** Convolutional Neural Network (CNN)
- **Image Processing:** OpenCV
- **Explainable AI:** Grad-CAM, LIME, SHAP
- **Data Processing and Evaluation:** NumPy, Matplotlib, scikit-learn
- **Development Environment:** Google Colab
- **Dataset Source:** Kaggle
- ## Project Workflow

1. **Dataset Collection:** Obtain brain MRI images from the Kaggle Brain Tumor MRI Dataset.
2. **Image Preprocessing:** Prepare and normalize MRI images for model input.
3. **CNN Model Training:** Train the CNN model to classify MRI images into four categories.
4. **Tumor Classification:** Predict the class as Glioma, Meningioma, No Tumor, or Pituitary.
5. **Grad-CAM Explainability:** Generate heatmaps to visualize image regions influencing the model's predictions.
6. **Model Evaluation:** Evaluate performance using test accuracy, a confusion matrix, and ROC curves.
7. ## How to Run the Project

1. Open the project notebook (`.ipynb`) in this GitHub repository.
2. Click **Open in Colab** if a Colab badge is provided, or download the notebook and upload it to [Google Colab](https://colab.research.google.com/).
3. In Google Colab, select **Runtime → Change runtime type** and choose a GPU if available.
4. Install any required libraries that are not already available in the environment.
5. Configure the Kaggle dataset download and access according to the notebook's instructions.
6. Run the notebook cells in order, from preprocessing and model setup through training, evaluation, and explainability.
## Dataset
This project uses the Brain Tumor MRI Dataset by Masoud Nickparvar, available on Kaggle.
- **Dataset Link:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- **Classes:** Glioma, Meningioma, No Tumor, and Pituitary
- **Data Type:** Brain MRI images
- **Usage:** Training and testing the CNN-based brain tumor classification model.
## Model Performance

- Overall test accuracy: 97.18%

## Training and Validation

![Training Curves](Training_and_Validation_curves.png)

## Confusion Matrix

![Confusion Matrix](Confusion%20Matrix.png)

## Class-wise Metrics

![Precision Matrix](confusion_matrix_precision.png)

![Recall Matrix](Confusion_matrix_recall.png)

## ROC Curve

![ROC Curve](Roc_curve.png)

## Grad-CAM Explainability

### Glioma

![Glioma Grad-CAM](glioma_gradcam.png)

### Meningioma

![Meningioma Grad-CAM](menongioma_gradcam.png)

### No Tumor

![No Tumor Grad-CAM](notumor_gradcam.png)

### Pituitary

![Pituitary Grad-CAM](pituitary_gradcam.png)

## LIME Explainability

![LIME Explanation](Lime_Explanation.png)

## SHAP Explainability

![SHAP Explanation](shap_explanation.png)
