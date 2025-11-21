# ST10082672_PDANPOE
Project Overview

This project forms Part 3 of the Programming for Data Analytics 2 (PDAN8412) module.
The goal is to develop and compare two deep-learning image classification models using the Animals-10 dataset from Kaggle, which contains 10 animal categories labelled in Italian.

I implemented:

A Baseline Convolutional Neural Network (CNN) built from scratch

A Transfer Learning Model (MobileNetV2) with pretrained ImageNet weights

The models were trained, evaluated, and compared based on accuracy, loss, classification reports, and confusion matrices.

Dataset: Animals-10 (Kaggle)

The dataset includes the following Italian-labelled classes:

cane, gatto, gallina, cavallo, pecora, elefante, farfalla, mucca, scoiattolo, ragno

Link: https://www.kaggle.com/datasets/alessiocorrado99/animals10

Images were split into training and validation directories using Keras ImageDataGenerator with augmentation.
