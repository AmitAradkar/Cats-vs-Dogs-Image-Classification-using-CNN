# Dogs Vs Cats Classification Problem 📸 🚀

The Dogs & Cats classification problem is a foundational project for learning how to use Convolutional Neural Networks (CNNs) to classify images as either dogs or cats. This project helps understand how to:

- Develop, evaluate, and use CNN models for image classification.
- Build a robust test harness for estimating model performance.
- Experiment with model improvements by tuning parameters.
- Save and load models to make predictions on new data.
  ![image](https://github.com/user-attachments/assets/78db23ed-623b-4c69-92fc-65cf48ac73bb)

---

## Table of Contents
1. [Introduction 💥](#introduction-%f0%9f%92%a5)
2. [Data Description](#data-description)
3. [Loading Libraries 📚](#loading-libraries-%f0%9f%93%96)
4. [Data Preparation: 📁](#data-extraction-%f0%9f%93%81)
5. [Data Exploration 📊](#data-exploration-%f0%9f%93%8a)
6. [Train Test Split](#train-test-split)
   - [Using Dataframe](#using-dataframe)
   - [Using Directory](#using-directory)
8. [Data Augmentation and Preprocessing,Data Preparation 🛠](#data-preparation)
   - [Image Data Generator](#image-data-generator)
   - [Using DataFrame](#using-dataframe-1)
   - [Using Directory](#using-directory-1)
9. [Deep Learning Model/Model Building ⚙️](#deep-learning-model-%e2%9a%99%ef%b8%8f)
   - [Model Layers](#model-layers)
   - [Callbacks](#callbacks)
   - [Compile Model](#compile-model)
   - [Fit Model](#fit-model)
   - [Plot Result](#plot-result)
10. [Evaluation](#evaluation)
11. [Prediction](#prediction)
12. [Visualize Classified Images](#visualize-classified-images)
13. [Submission](#submission)
14. [Conclusion](#conclusion)

---

## Introduction 💥

In this project, we will explore how to develop a CNN to classify images of dogs and cats.

### Key Learning Objectives:
- Load and prepare images for training purposes.
- Split data for training and validation.
- Apply Data Augmentation techniques.
- Develop a CNN model using Keras, including selecting parameters for better performance.
- Evaluate the model's performance.
- Save and load the model for future predictions.
- Visualize the confusion matrix for a trained model.

---

## Data Description

The dataset consists of:
- **Training Data:** 25,000 labeled images of dogs and cats.
- **Testing Data:** Test files (`test1.zip`) to predict labels.

### Labels:
- `1 = Dog`
- `0 = Cat`

---

## To Get Started:
1. **Download Dataset:** Obtain the Dogs vs. Cats dataset.
2. **Load Libraries:** Use essential libraries such as TensorFlow, Keras, Pandas, and Matplotlib.
3. **Data Preprocessing:** Handle missing values and encode labels if necessary.
4. **Build the Model:** Create a CNN using Keras with appropriate layers and parameters.
5. **Train and Evaluate:** Train the model, validate it, and tune hyperparameters.
6. **Save the Model:** Store the trained model for future predictions.
7. **Visualize Results:** Use Matplotlib to plot training/validation accuracy and loss.

 **For code:** please refer attached Cats_vs_ Dogs_Image_Classification_using_CNN.ipynb file


---
