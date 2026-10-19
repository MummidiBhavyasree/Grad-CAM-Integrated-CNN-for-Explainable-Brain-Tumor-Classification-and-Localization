# Grad-CAM-Integrated-CNN-for-Explainable-Brain-Tumor-Classification-and-Localization
Explainable deep learning framework for brain tumor classification and localization using CNN and Grad-CAM on MRI images, achieving 97% test accuracy.
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
