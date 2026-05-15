# Status: Model Training & Evaluation (Notebook-Based)

## Note:

This project is implemented and evaluated using a Jupyter Notebook (.ipynb) environment, which is well-suited for iterative model development, experimentation, and visualization. The notebook format enables step-by-step inspection of data preprocessing, model architecture, training behavior, and performance metrics.

### Advantages of Notebook-Based Implementation
Exploratory model development

Enables rapid experimentation with CNN architectures, hyperparameters, and preprocessing techniques.

Inline visualizations help analyze class distribution, sample images, and training trends.

Transparent training pipeline

Clear separation of stages:
data loading → preprocessing → augmentation → model definition → training → evaluation

Facilitates debugging and academic/technical review.

Reproducibility

All preprocessing steps, model configurations, and results are documented in one executable file.

Suitable for academic evaluation and technical interviews.

Performance monitoring

Training and validation accuracy/loss curves allow detection of overfitting or underfitting.

Confusion matrix and accuracy metrics help evaluate class-wise performance.


### Model & Data Characteristics
Dataset Handling

Image dataset consisting of multiple skin disease classes.

Preprocessing includes:

Image resizing

Normalization

Label encoding

Data augmentation applied to improve generalization and reduce overfitting.

Model Architecture

Custom Convolutional Neural Network (CNN) with multiple convolution, pooling, and dense layers.

Designed to extract hierarchical spatial features from skin images.

Optimized for multi-class classification.

Training Strategy

Supervised learning using categorical cross-entropy loss.

Validation split used to monitor generalization.

Accuracy used as the primary evaluation metric.

### Future Deployment Options
1. Streamlit (Recommended for this project)

Convert the trained CNN model into an interactive web app.

Users can upload skin images and receive predictions.

Maintains Python-based ML pipeline.

2. REST API + Frontend

Expose the trained model via a Flask/FastAPI backend.

Frontend (React or simple UI) sends images to the API for inference.


### This project prioritizes:

Model accuracy

Architectural experimentation

Training analysis

Educational and evaluation clarity

Hence, a Jupyter Notebook is the correct and professional choice
