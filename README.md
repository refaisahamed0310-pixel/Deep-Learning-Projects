# Deep Learning Projects

A collection of hands-on Deep Learning notebooks developed using Python and TensorFlow/Keras. The projects explore Convolutional Neural Networks (CNNs) and transfer learning for image classification across fruit, animals, facial attributes, medical images, emotions, and currency.

The notebooks demonstrate dataset preparation, image loading, model construction, training, prediction, and visualization of training performance.

## Projects

| Project | Task | Main Techniques |
|---|---|---|
| Fruit Image Classification | Classifies apple, banana, and guava images | CNN, softmax classification |
| Beard Detection | Classifies images into beard/no-beard categories | CNN, binary classification |
| Brain Tumor Classification | Classifies brain scan images into the dataset's two classes | CNN, binary classification |
| Cat and Dog Classification | Distinguishes cat and dog images | CNN, binary classification |
| Emotion Classification | Classifies images into the dataset's emotion classes | CNN, binary classification workflow |
| Sri Lanka and India Currency Classification | Classifies currency images | VGG16 transfer learning |

## Technologies & Tools

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow, Keras
- **Image Processing:** Pillow, NumPy
- **Data Visualization:** Matplotlib
- **Development Environments:** Jupyter Notebook, Google Colab

## Concepts Covered

- Image dataset organization and splitting
- Image resizing and normalization
- Convolutional Neural Networks (CNN)
- Convolution and pooling layers
- Dense layers and dropout
- Binary and multi-class classification
- Transfer learning with VGG16
- Model training and validation
- Prediction and confidence scores
- Training/validation accuracy visualization

## Repository Structure

```text
Deep-Learning-Projects/
├── Fruit-Image-Classification/
├── Beard-Detection/
├── Brain-Tumor-Classification/
├── Cat-Dog-Classification/
├── Emotion-Classification/
├── Currency-Classification-Transfer-Learning/
├── README.md
├── requirements.txt
└── .gitignore
```

## Getting Started

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebooks using Jupyter Notebook, JupyterLab, or Google Colab. Some notebooks were originally developed with Google Colab paths; update the dataset paths to match your own environment.

## Dataset Information

Datasets are not included in this repository. Download or provide the relevant image datasets separately and organize them into class-specific folders.

For notebooks using `image_dataset_from_directory`, use a structure similar to:

```text
dataset/
├── class_1/
│   ├── image_001.jpg
│   └── image_002.jpg
└── class_2/
    ├── image_001.jpg
    └── image_002.jpg
```

Check each notebook's dataset setup cells for its expected folder names and paths before execution.

## Important Notes

- These are educational and portfolio projects, not validated clinical or production systems.
- The brain tumor notebook is an image-classification experiment and must not be used for medical diagnosis or treatment decisions.
- The beard and emotion notebooks contain dataset path/class-label assumptions that must be checked against the actual dataset folders.
- Model performance has not been independently re-evaluated because the original datasets are not included.
- GPU acceleration is recommended for training larger CNN models.

## Author

**Ahamed Refai S**

Computer Science Graduate | Python Developer | AI & Machine Learning | Data Science | Backend Development

- **GitHub:** https://github.com/YOUR-USERNAME
- **LinkedIn:** https://www.linkedin.com/in/ahamed-refai-s-6775b2310

---

*Building and exploring image-based intelligent systems with Deep Learning.*
