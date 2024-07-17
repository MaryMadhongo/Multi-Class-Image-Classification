# Multi-Class-Image-Classification
 Deep Learning Models on CIFAR-10 Dataset

### Description
This project involves training and evaluating various deep learning models on the CIFAR-10 dataset using TensorFlow and Keras. It includes steps for data preparation, model building, training, and evaluation, aiming to achieve high performance in image classification.

### Key Steps
1. **Data Preparation:**
   - Load CIFAR-10 dataset.
   - Normalize images.
   - One-hot encode the labels.

2. **Model Building:**
   - Utilize custom layers.
   - Define models using Sequential API or Functional API.
   - Apply techniques like Dropout, BatchNormalization, and L2 regularization.

3. **Model Compilation and Training:**
   - Compile models with optimizers like Adam, SGD, and RMSprop.
   - Use callbacks such as EarlyStopping and ReduceLROnPlateau.
   - Train models on training data and validate using validation data.

4. **Evaluation:**
   - Evaluate models using metrics such as accuracy, confusion matrix, classification report, and AUC.
   - Visualize results with plots for accuracy and loss.

### Installation
Ensure you have the following libraries installed:
- TensorFlow
- Keras
- Matplotlib
- Pandas
- Scikit-learn
- Seaborn


Install them using pip:
```
pip install tensorflow keras matplotlib pandas scikit-learn seaborn lightgbm
```

### Running the Project
1. Load the Jupyter notebooks .
2. Run the cells sequentially to preprocess data, build models, train them, and evaluate their performance.

### Conclusion
This project demonstrates the application of various deep learning techniques to achieve high performance in image classification tasks using the CIFAR-10 dataset. It includes robust methods for model building, training, and evaluation, ensuring reliable and accurate results.
