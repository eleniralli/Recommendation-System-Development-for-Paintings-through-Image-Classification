Recommendation System for Paintings through Image Classification
 
This project aims to develop a recommendation system that classifies paintings based on specific target labels and suggests similar artworks to enhance user engagement.
 
Objectives and Steps:
Deep-learning Classification Model
Create a multi-output classifier to predict five target labels: artist, subject, style, materials, and period of the painting.
 
Recommendation System:
Develop a system that recommends similar paintings based on predicted labels and extracted image features to maximize user engagement.
 
Model Architectures:
Two deep learning approaches were used: Convolutional Neural Networks (EfficientNetB3, VGG16, VGG19) and Vision Transformer (Google's ViT model).
 
Performance Comparison:
The custom Vision Transformer (ViT) classifier outperformed the CNN-based models in terms of accuracy.
 
Embedding-based Recommendation:
The selected ViT model was used to extract both visual and label features as embeddings, which were then utilized to calculate the similarity between paintings for the recommendation system.
Dataset
 
The initial dataset utilized is collected from "Best Artworks of All Time" and can be accessed at Kaggle. The "data.csv" file is included in this repository.
 
Part 1:
In this part, each of the 400 selected image titles is mapped to its corresponding file path in the images folder for use in the project.
 
Part 2:
The development of the multi-output classification model and recommendation system will be implemented in Part 2, utilizing various architectures to enhance predictive capabilities and suggest artworks to users effectively.

The weights of the best epoch are from epoch 47. If you prefer not to use all the weights, you can use only them.

Authors:
Papadimitriou Anna, Registration number: f2822311
Ralli Eleni, Registration number: f2822312
Lakkas-Pyknis Evangelos, Registration number: f2822306
Mesolora Stamatoula Gerasimoula, Registration number: f2822308
 
Course Information:
MSc Business Analytics, Athens University of Economics and Business
Machine Learning and Content Analytics
