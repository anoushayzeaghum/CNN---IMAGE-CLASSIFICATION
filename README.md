# CNN - IMAGE CLASSIFICATION
This assignment embarks on leveraging Convolutional Neural Networks (CNNs) to execute an image classification pipeline for categorizing natural scene images into distinct classes. With a dataset encompassing 25,000 150x150-pixel images distributed among six categories, including Buildings, Forest, Glacier, Mountain, Sea, and Street, the task involves training on 14,000+ images, cross-validating using 3,000+ images, and testing with 7,000+ images. We preferred CNN architecture, be it custom-built with fundamental layers or employing pre-implemented models in frameworks like Keras or PyTorch. Through this we delve into the domain of modern machine learning, exploring the robustness of CNNs in deciphering complex visual data for practical image recognition and classification purposes.

## DATASET INFORMATION
This is the Data of Natural Scenes around the world. It contains around 25k images of size 150x150 distributed under 6 categories i.e. Buildings, Forest, Glacier, Mountain, Sea and Street. The Train, Test and Prediction data is separated in each zip files. There are around 14k images in Train, 3k in Test and 7k in Prediction. You are supposed to work in following manner:
- Training set = 14k+ 150x150 Images in seg_train folder for trainingspread.
- Validation set = 3k+ 150x150 Images in seg_test folder for cross-validationspread.
- Testset = 7k+ 150x150 Images in seg_pred folder as testspread.

## IMPORTED DIFFERENT LIBRARIES
1. **NumPy:** Used for numerical computations and array manipulations in Python.
2. **Pandas:** Essential for data manipulation, offering data structures and operations for structured data sets.
3. **Matplotlib:** Primarily utilized for creating visualizations like plots, charts, and graphs.
4. **Seaborn:** Built on top of Matplotlib, it enhances data visualization, particularly for statistical graphics.
5. **Warnings:** Provides control over warning messages; in this case, used to ignore unnecessary warnings.
6. **Scikit-learn:** Offers tools for machine learning, including functions for evaluation metrics like confusion matrices and accuracy scores.
7. **OS:** Allows interaction with the operating system for tasks like file operations (reading/writing).
8. **TensorFlow:** An open-source machine learning framework used for building and training neural networks.

## DEFINING CLASSES OF DATASET
Defined The Classes in following Categories:
1. Buildings
2. Forest
3. Glacier
4. Mountain
5. Sea
6. Street

## IMPLICATION OF DIFFERENT FUNCTIONS FOR IMAGE CLASSIFICATION
Functions used for following purposes:

- Reading Image file names
- Checking Class imbalances in Dataset
- Plotting Images from Classes
- Generating Predictions
- Plotting Confusion Matrix
- Preparing Images for Prediction
- Checking distribution across classes for Train and Test Set

## USE OF DIFFERENT MODELS AND LAYERS
The different models and layers used are:
1. Sequential
2. Conv2D
3. MaxPooling2D
4. Flatten
5. Dense
6. Relu
7. Softmax
 
# RESULTS
- Calculated the Confusion Matrix
- Plotted Training and Validation Accuracy
- Plotted Training and Validation Loss
- Calculated the Accuracy of Training Set
- Calculated the Accuracy of Training Set
  
