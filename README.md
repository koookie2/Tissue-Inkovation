# Tissue-Inkovation
A GUI tool to predict bioink printability and viability in an in-vivo-like environment before creation.

## Overview
Hello Inkovators! Tissue Inkovation is a machine learning project created for the TJHSST's 2025 Biocode Hackathon. The goal was to design a user-friendly page for users to access this model. This page provides a more convenient way to get predictions for bioink printability and viability. The highest-accuracy model attained an F1 score of 0.9919, which signifies a strong balance in the model's precision and accuracy.

Here is the Google Colab link for the project's development (NOT FINAL MODEL)! https://colab.research.google.com/drive/1G-n0ONwAnO7ySxkZGCSGHe7PN0fNpbJ3?usp=sharing.

Here is the Google Colab link for the project's final GUI! https://colab.research.google.com/drive/1KeYoT-e5uHB98qPvVIGxsy8DzOIi-FjT?usp=sharing.

## Directions
1. Ensure that your browser is up to date, along with the latest versions of all necessary packages/dependencies (Tensorflow, Numpy, and tkinter).
2. Download the most recent version of this repository.
3. Either go to this Giadio link: https://702d22feb0eddb70d1.gradio.live or extract, download, and run the TissueInkovation.pkl file.
4. Enter all of the requested parameters (MUST be numbers) in the text boxes or input a .xlsx file into the batch option (sample file in Samples section).
5. Receive your prediction! (Predictions will either be high or low for the printability and viability). A prediction of high for both the printability and viability indicates the bioink will be functional in the real world while a value of low for either category indicates that it will be nonfunctional. 

Enjoy!

## Samples
If you would like to analyze the dataset or try out some sample values, please download the dataset.

Sample batch data: https://drive.google.com/file/d/1gHUvhHkqtB_O9WvlWw_meR3XGbXZeDYh/view?usp=sharing

Sample individual data: 200,5,0.05,10,150,400,37,25,30,60,0.8,1.05,5,2,0.1,100000,7.4,150,1.5,500,50,0.9,0.8,35,45,22,15,0.2,0.3,85,100,45,0.002,1.2,0.5,2,7,120,0.7,0.95,10,365,0.85,90,5000,0.001,0.5,70,75

Dataset: https://drive.google.com/file/d/1tOmy0oriRnDdH8OdNZeDGSK1xJRp_gFJ/view?usp=sharing

## Contributors
 - Sharat Sakamuri
 - Kavin Wesley
