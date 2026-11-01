# Deep Learning Projects

A curated collection of hands-on **Deep Learning and Computer Vision projects** developed using Python, TensorFlow, and Keras. This repository demonstrates practical applications of Convolutional Neural Networks (CNNs), image classification, binary and multi-class prediction, and transfer learning.

The projects explore how deep learning models can learn visual patterns from image datasets and perform classification tasks across different domains, including fruits, animals, facial attributes, medical images, emotions, and currency.

Each project is organized as a Jupyter Notebook and covers key stages of a typical deep learning workflow, from dataset preparation and preprocessing to model development, training, evaluation, and prediction.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Projects Included](#projects-included)
- [Technology Stack](#technology-stack)
- [Deep Learning Concepts Covered](#deep-learning-concepts-covered)
- [Repository Structure](#repository-structure)
- [Installation and Setup](#installation-and-setup)
- [Running the Projects](#running-the-projects)
- [Dataset Preparation](#dataset-preparation)
- [Model Development Workflow](#model-development-workflow)
- [Important Considerations](#important-considerations)
- [Future Improvements](#future-improvements)
- [Author](#author)

## Project Overview

This repository contains six independent deep learning projects focused on image classification and computer vision.

The projects demonstrate:

- Preparing and organizing image datasets.
- Resizing and preprocessing images for model input.
- Building CNN architectures using TensorFlow/Keras.
- Training binary and multi-class classification models.
- Applying transfer learning with a pre-trained VGG16 model.
- Generating predictions from unseen images.
- Visualizing training and validation performance.

The notebooks are intended for learning, experimentation, and demonstrating practical deep learning skills.

## Projects Included

| No. | Project | Description | Techniques |
|---|---|---|---|
| 01 | **Fruit Image Classification** | Classifies fruit images into Apple, Banana, and Guava categories. | CNN, Multi-class Classification, Softmax |
| 02 | **Beard Detection** | Classifies facial images into Beard and No-Beard categories. | CNN, Binary Classification |
| 03 | **Brain Tumor Classification** | Performs image classification on brain scan images using the dataset's two classes. | CNN, Binary Classification |
| 04 | **Cat and Dog Classification** | Distinguishes between cat and dog images using a CNN-based model. | CNN, Binary Classification |
| 05 | **Emotion Classification** | Explores image-based emotion classification using a CNN workflow. | CNN, Image Classification |
| 06 | **Sri Lanka and India Currency Classification** | Classifies currency images using a VGG16-based transfer learning approach. | VGG16, Transfer Learning |

### Project Details

**1. Fruit Image Classification**

A multi-class image classification project that identifies fruit categories from input images.

- Classes: Apple, Banana, and Guava.
- Model approach: Convolutional Neural Network.
- Prediction: Selects the class with the highest predicted probability.

**2. Beard Detection**

A binary image classification project that explores facial attribute recognition.

- Classes: Beard and No Beard.
- Model approach: CNN-based binary classification.
- Objective: Learn visual features associated with facial hair.

**3. Brain Tumor Classification**

An educational image classification experiment using brain scan images.

- Dataset: Brain scan images organized into two classes.
- Model approach: CNN-based binary classification.
- Objective: Explore image feature learning and classification using medical-image datasets.

**4. Cat and Dog Classification**

A computer vision project that distinguishes between two animal categories.

- Classes: Cat and Dog.
- Model approach: CNN-based binary classification.
- Objective: Identify visual differences between animal images.

**5. Emotion Classification**

An image classification project exploring emotion-related visual patterns.

- Model approach: CNN-based classification workflow.
- Objective: Learn image features and classify images into the dataset's emotion categories.
- Note: Actual class labels depend on the dataset organization.

**6. Sri Lanka and India Currency Classification**

A transfer learning project that uses a pre-trained VGG16 architecture for currency image classification.

- Architecture: VGG16.
- Approach: Transfer learning.
- Objective: Reuse pre-trained visual feature representations for a currency classification task.

---

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Deep Learning Framework | TensorFlow, Keras |
| Neural Network Architecture | Convolutional Neural Networks (CNNs) |
| Transfer Learning | VGG16 |
| Numerical Computing | NumPy |
| Data Handling | Pandas |
| Image Processing | Pillow |
| Data Visualization | Matplotlib |
| Development Environment | Jupyter Notebook, Google Colab |
| Version Control | Git, GitHub |

## Deep Learning Concepts Covered

The projects provide practical exposure to the following concepts:

**Image Processing and Preprocessing**
- Image loading and dataset organization.
- Image resizing and normalization.
- Training and validation dataset preparation.
- Data augmentation and image transformation.

**Convolutional Neural Networks**
- Convolutional layers.
- Pooling layers.
- Flattening operations.
- Dense layers.
- Dropout and regularization.
- Feature extraction from images.

**Classification Techniques**
- Binary classification.
- Multi-class classification.
- Sigmoid and Softmax activation functions.
- Prediction probabilities and confidence scores.
- Classification thresholding.

**Model Training and Evaluation**
- Model compilation and training.
- Training and validation accuracy.
- Loss monitoring.
- Prediction on input images.
- Visualization of training performance.

**Transfer Learning**
- Pre-trained VGG16 architecture.
- Reusing pre-trained feature extraction layers.
- Adapting a model for a custom classification task.

---

## Repository Structure

```text
Deep-Learning-Projects/
│
├── Fruit-Image-Classification/
│   └── fruit_classification.ipynb
│
├── Beard-Detection/
│   └── beard_detection.ipynb
│
├── Brain-Tumor-Classification/
│   └── brain_tumor_classification.ipynb
│
├── Cat-Dog-Classification/
│   └── cat_dog_classification.ipynb
│
├── Emotion-Classification/
│   └── emotion_classification.ipynb
│
├── Currency-Classification-Transfer-Learning/
│   └── currency_classification.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

*Notebook filenames above illustrate the intended organization. Use the actual filenames committed in each project folder.*

## Installation and Setup

### Prerequisites

Make sure the following are installed:

- Python 3.9 or later (a compatible TensorFlow version is required).
- pip package manager.
- Jupyter Notebook or JupyterLab.
- Git (optional, for cloning the repository).

### 1. Clone the Repository

```bash
git clone https://github.com/refaisahamed0310-pixel/Deep-Learning-Projects.git
```

Navigate into the project directory:

```bash
cd Deep-Learning-Projects
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Activate it on Linux/macOS:

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
python -m pip install --upgrade pip
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, open the repository in VS Code and run the notebooks using its Jupyter extension.

## Running the Projects

Each project is maintained independently.

1. Open the project folder you want to explore.
2. Launch its Jupyter Notebook.
3. Review the dataset setup and preprocessing cells.
4. Update the dataset paths according to your local environment.
5. Execute the notebook cells in their original order.
6. Review the model training output and visualizations.
7. Test predictions using suitable input images.

**Google Colab users:** Some notebooks were originally developed using Google Colab. Update any Colab-specific paths and upload or mount the required datasets before running them.

## Dataset Preparation

The datasets are not included in this repository. Users must obtain the appropriate datasets separately and organize them according to each notebook's requirements.

For notebooks using directory-based image loading, a typical dataset structure looks like this:

```text
dataset/
│
├── class_1/
│   ├── image_001.jpg
│   ├── image_002.jpg
│   └── image_003.jpg
│
└── class_2/
    ├── image_001.jpg
    ├── image_002.jpg
    └── image_003.jpg
```

For multi-class classification, create a separate folder for each class.

**Before training:**
- Verify the dataset folder names.
- Check the expected class labels and class order.
- Confirm image formats and dimensions.
- Update dataset paths in the notebook.
- Ensure the training and validation datasets are correctly configured.

## Model Development Workflow

The general workflow followed across these projects is:

1. **Dataset Collection:** Obtain and organize the required image data.
2. **Preprocessing:** Load, resize, and normalize images.
3. **Dataset Preparation:** Prepare training and validation data.
4. **Model Construction:** Build CNN architectures or adapt a pre-trained model.
5. **Model Training:** Train the model using the prepared dataset.
6. **Performance Visualization:** Examine training and validation accuracy and loss.
7. **Prediction:** Test the model using input images.
8. **Result Analysis:** Review predictions and identify possible improvements.

## Important Considerations

- These projects are intended for educational and portfolio purposes.
- Model performance depends on dataset quality, class distribution, preprocessing, and training configuration.
- The notebooks have not been independently re-evaluated using the original datasets in this repository.
- Dataset paths and class-label assumptions should be verified before execution.
- The brain tumor classification project is strictly an educational experiment. It is not a validated medical diagnostic tool and must not be used for diagnosis or treatment decisions.
- Beard and emotion classification results may be affected by dataset quality, class balance, and label assumptions.
- GPU acceleration is recommended for larger image datasets and computationally intensive training.
- Results from these notebooks should not be interpreted as production-level model performance.

## Future Improvements

Potential improvements for these projects include:

- Adding independent train, validation, and test datasets.
- Applying systematic hyperparameter tuning.
- Evaluating models using precision, recall, F1-score, and confusion matrices.
- Improving generalization through data augmentation and regularization.
- Comparing different CNN architectures.
- Exploring additional transfer learning models such as MobileNetV2 and EfficientNet.
- Developing user-friendly interfaces for image prediction.
- Deploying selected models through APIs or mobile applications.

---

## Author

**Ahamed Refai S**

Computer Science Graduate | Python Developer | AI & Machine Learning | Data Science | Backend Development

- **GitHub:** [refaisahamed0310-pixel](https://github.com/refaisahamed0310-pixel)
- **LinkedIn:** [Ahamed Refai](https://www.linkedin.com/in/ahamed-refai-s-6775b2310/)

---

*Exploring computer vision and building intelligent image classification systems with Deep Learning.*

If you find this repository useful, feel free to ⭐ star the project!
