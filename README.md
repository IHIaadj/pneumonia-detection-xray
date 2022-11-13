# pneumonia-detection-xray
This repository contains a cap-stone project for the Udacity "Applying AI to 2D Medical Imaging Data" course, part of the AI for Healthcare Nanodegree program.

In this project, I train a CNN to classify a given chest x-ray for the presence or absence of pneumonia using the NIH Chest X-ray Dataset. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, the file FDA.pdf summarize the model description, training procedure and FDA validation process. 

# Project Structure:
* *EDA.ipynb*: This file performs EDA on NIH dataset to extract pneumonia related features.
* *Build and train model.ipynb*: Builds and fine-tune VGG-16 model and evaluate the model using recall and f1 score.
* *Inference.ipynb*: Performs clinical workflow integration using DICOM data files.
* *FDA.md* and *FDA.pdf*: FDA submission.
