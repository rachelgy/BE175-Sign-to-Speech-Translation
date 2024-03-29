# BE175-Sign-to-Speech-Translation
BE175 Final Project 
By Rachel Yu & Clara Kang

### Project Overview

#### Introduction/Motivation
This project focuses on implementing a machine learning algorithm to aid in the translation of sign language gesture recognition, based on the paper "Sign-to-speech translation using machine learning assisted stretchable sensor arrays". Sign language bridges communication gaps for those with speech impediments but faces limitations in accessibility. By utilizing wearable technology and machine learning, this project aims to make sign language more approachable, enhancing inclusivity in communication.

#### Methods
The project approach consists of five main stages: signal collection, data preprocessing, dimensionality reduction, classification, and model evaluation. Signal data is collected using yarn-based stretchable sensor arrays and a wireless PCB. Dimensionality reduction techniques such as PCA and LDA are employed to extract relevant features. Classification is performed using SVM with various kernel types, and model performance is evaluated using metrics like accuracy and confusion matrices.

#### Result
The optimized SVM model achieved an accuracy of 87%, indicating high success in predicting gesture signals. While the achieved accuracy is similar to the paper's reported 98%, limitations in data usage and the use of LDA instead of PCA for dimensionality reduction are acknowledged. Future steps involve exploring methods to include more data points while enhancing the efficiency of LDA.

### Conclusion
This project demonstrates the potential of machine learning and wearable technology in improving accessibility and inclusivity in communication for individuals with speech impediments. Further refinement and exploration of techniques can lead to even higher accuracy levels, advancing the field of sign language translation.

