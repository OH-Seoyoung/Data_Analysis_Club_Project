# Data Analysis Club Assignment (20200514 ~)
Activities in data analysis club - Programming Assignment

## Description
> 0. Python Quiz for newcomer | [Quizs](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/tree/master/Assignment_for_newcomer)
> 1. Supervised Learning : MNIST Handwriting Recognition
> 2. Unsupervised Learning : IRIS data Clustering
> 3. Kaggle Tutorial : Data Analysis and Machine Learning with POKEMON stat & image dataset  
> 4. Kaggle Competition : Predict Future Sales  
> 5. Kaggle Competition : Plant Seedlings Classification  

## Assignment 1. Supervised Learning : MNIST Handwriting Recognition (20200529)
[Presentation](My_Assignment/Assignment1_MNIST_handwriting_recognition/20200529_assignment1.pdf) | [Code1](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment1_MNIST_handwriting_recognition/1_SLP_with_MNIST.ipynb), [Code2](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment1_MNIST_handwriting_recognition/2_MLP_with_MNIST.ipynb)

<img src="https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/BASELINE_code/Assignment1_MNIST_handwriting_recognition/assignment%201.jpg"  width="500" height="380">  

## Assignment 2. Unsupervised Learning : IRIS data Clustering (20200723)
#### This project is maintained by [최연석](https://github.com/YeonSeok-Choi), 오서영 
| [Presentation](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment2_IRIS_Clustering/20200723_assignment2.pdf) | 
[Code](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment2_IRIS_Clustering/IRIS_Clustering_with_AgglomerativeClustering.ipynb)


<img src="https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/BASELINE_code/Assignment2_IRIS_Clustering/assignment%202.jpg"  width="500" height="380">  

## Assignment 3. Kaggle Tutorial : DA and ML with POKEMON stat & image dataset (20200814)
| [Presentation](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment3_Data_Analysis_and_Machine_Learning_with_POKEMON_stat%26image_dataset/20200814_assignment3.pdf) | 
[Code](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment3_Data_Analysis_and_Machine_Learning_with_POKEMON_stat%26image_dataset/Pokemon_image_generation_with_GANs.ipynb)


### Dataset  
```
[1] Pokemon with stats, https://www.kaggle.com/abcsds/pokemon  
[2] Pokemon Image Dataset, https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types  
```
### Pokemon generation with **GANs**
- Vanilla GAN with Keras
- Convert RGBA to RGB (PNG to JPG)  

## Assignment 4. Kaggle Competition : Predict Future Sales (20200828)
#### This project is maintained by [최연석](https://github.com/YeonSeok-Choi), 오서영  
| [Presentation](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment4_Predict_Future_Sales/20200828_assignment4.pdf) | 
[Code1](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment4_Predict_Future_Sales/Predict_Future_Sales_with_LSTM.ipynb), [Code2](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment4_Predict_Future_Sales/Predict_Future_Sales_with_Simple_Xgboost.ipynb)


### Competition
```
[1] Predict Future Sales, https://www.kaggle.com/c/competitive-data-science-predict-future-sales
```

### Results  
#### 1. LSTM  
RMSE error : 1.02245 (10 iterations)  
RMSE error : 1.02711 (60 iterations)  

#### 2. XGBRegressor
RMSE error : 1.43613  

## Assignment 5. Kaggle Competition : Plant Seedlings Classification (20200918)  
#### This project is maintained by 오서영, [허지혜](https://github.com/jihyeheo)
| [Presentation](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment5_Plant_Seedlings_Classification/20200918_assignment5.pdf) |  [Code1](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment5_Plant_Seedlings_Classification/Plant_Seedlings_Classification_with_CNN.ipynb), [Code2](https://github.com/OH-Seoyoung/Data_Analysis_Club_Assignment/blob/master/My_Assignment/Assignment5_Plant_Seedlings_Classification/Plant_Seedlings_Classification_with_Resnet.ipynb)


### Competition
```
[1] Plant Seedlings Classification, https://www.kaggle.com/c/plant-seedlings-classification/overview
```

### Results  
#### 1. Baseline CNN  
Train accuracy: 72.50%  
Val accuracy: 69.38%    

#### 2. Resnet  
Train accuracy: 86.25%  
Val accuracy: 80%    

