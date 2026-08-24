Accident Detection System
1. What is Accident Detection System?
An accident Detection System is designed to detect accidents via video or CCTV footage. Road accidents are a significant problem for the whole world. Many people lose their lives in road accidents. We can minimize this issue by using CCTV accident detection. This repository majorly explores how CCTV can detect these accidents with the help of Deep Learning.

2. Prerequisites
To use this project Python Version > 3.6 is recommended.
To contribute to this project, knowledge of basic python scripting, Machine Learning, and Deep Learning will help.
3. Getting Started - How to use it?
Clone this repository
To install all the packages required to run this python program pip install -r requirements.txt

Note: This project requires a camera. So make sure you have a connected camera to your device. You can also use a downloaded video if not using a camera.

Run
Before running the program, you need to run the accident-classification.ipynb file which will create the model_weights.h5 file. Then, to run this python program, you need to execute the main.py python file.

4. Description
This program includes 4 things.

data: Kaggle dataset on Accident Detection from CCTV footage.
accident-classification.ipynb: This is a jupyter notebook that generates a model to classify the above data. This file generates two important files model.json and model_weights.h5.
detection.py: This file loads the Accident Detection system with the help of model.json and model_weights.h5 files.
camera.py: It packs the camera and executes the detection.py file on the video dividing it frame by frame and displaying the percentage of the prediction in the accident (if present) in the frame.
About

Identifying road accident through cnn

Resources
Readme
Activity
Stars
1 star
Watchers
0 watching
Forks
0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Contributors
No contributors
Languages
Jupyter Notebook
99.9%
Python
0.1%
Suggested workflows
Based on your tech stack

Publish Python Package logo
Publish Python Package
Publish a Python Package to PyPI on release.
By GitHub Actions
Pylint logo
Pylint
Lint a Python application with pylint.
By GitHub Actions
Python application logo
Python application
Create and test a Python application.
By GitHub Actions
More workflows
Footer
© 2026 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Community
